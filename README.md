# Madhu-Siri: Bee-Farmer Harmony

Madhu-Siri is an Android prototype for village-level coordination between beekeepers and farmers. Beekeepers pin hive locations, farmers send a spray ping before pesticide use, and hives within 2 km are flagged for a 4-hour closure window.

## What is included

- Hive Map with Google Maps markers for pinned hives and the latest spray location.
- Spray Alert screen with a farmer role action: `Spraying Today`.
- 2 km radius matching using haversine distance.
- Bee Health dashboard for hive strength and honey production.
- Bee-Friendly Tips for safe pesticide timing and pollinator protection.
- Honey and nature color palette with Material 3 Compose UI.

## Open in Android Studio

1. Open this folder in Android Studio.
2. Let Gradle sync dependencies.
3. Add your Google Maps API key in `app/src/main/res/values/strings.xml`.
4. Run the `app` configuration on an emulator or Android device.

## Firebase setup for real-time alerts

The prototype currently simulates alerts in memory so students can demo the flow quickly. For production or a hackathon final demo:

1. Create a Firebase project.
2. Add an Android app with package `com.madhusiri.app`.
3. Download `google-services.json` into `app/`.
4. Re-enable the Google Services plugin in `app/build.gradle.kts`:

```kotlin
plugins {
    id("com.google.gms.google-services")
}
```

Recommended Firestore collections:

```text
hives/{hiveId}
  ownerId: string
  ownerName: string
  name: string
  lat: number
  lng: number
  geohash: string
  colonyStrength: string
  honeyKgThisMonth: number

sprayAlerts/{alertId}
  farmerId: string
  farmerName: string
  crop: string
  lat: number
  lng: number
  radiusKm: number
  activeUntil: timestamp
  createdAt: timestamp
```

For the success criterion, send notifications only to beekeeper devices whose hives are within 2 km of the spray alert. At scale, store geohashes and query neighboring geohash bounds before applying the exact haversine distance check.

## Student demo script

1. Switch role to `Farmer`.
2. Open `Spray Alert`.
3. Tap `Spraying Today`.
4. Switch to `Hive Map` to see the spray marker.
5. Switch back to `Spray Alert` to see affected hives and closure guidance.
6. Open `Health` to show editable owner hive locations and production tracking.
