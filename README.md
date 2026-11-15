# TimeBuddy – World Time Planner

A Flutter Android app MVP with a minimal white interface.

## Features in this starter build
- World clock cards for popular cities
- Search cities
- Save favorite cities locally
- Time zone converter with date/time picker
- Meeting overview across selected cities
- Dark/light theme toggle
- IANA time zones with daylight-saving-aware timezone database

## Cloud build without installing anything on your PC

1. Create a GitHub account if you do not already have one.
2. Create a new empty repository named `timebuddy`.
3. In the repository, use **Add file → Upload files** and upload the contents of this project ZIP (including hidden `.github` folder).
4. Commit the files to the `main` branch.
5. Open the repository's **Actions** tab.
6. Select **Build TimeBuddy APK** and run it, or wait for the push-triggered build.
7. When the workflow completes, open the run and download the `timebuddy-preview-apk` artifact.
8. Extract the downloaded artifact and install `app-debug.apk` on your Android phone.

No local Windows development software is required. GitHub account and internet access are required.

## Important
This is a first MVP source build, not a verified production release. The cloud workflow runs Flutter analysis and the included widget test before building the APK. A real-device review, further feature QA, privacy review, Play Console compliance and production AdMob configuration remain necessary before publishing.

No production AdMob IDs are included. Do not click your own ads.
