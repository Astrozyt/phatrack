# phatrack
An experimental Android health tracker app that respects privacy and is built with Tauri.

## MVP features
- Built on Tauri 4
- Compiles to/Usable on Android phones (grapheneOS)
- Ability to register a user (local profile)
- Ability to add different measurements that are saved under the profile:
    - Weight
    - Muscle mass
    - Fat percentage
    - Different length measurements of the body
    - Measurements of blood values, i.e. blood sugar & ketones.
    - Calculated GKI
- Ability to display time series (e.g. BMI) in a nice visual way.

## Ambitious features:
- Built-in image recognition, to read values from "dumb scales".
- Valuable connection to at least one type of smart watch.
- Connection to health features of the phone (Android Health et al.)

## Final features
- Make app available on at least one app store, preferrably fDroid.
- Containerized server app (runnable on portainer on a home server), that syncs data and makes them accessible on other devices.
