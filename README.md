# EasyTagg update server files

Upload `version.json` to the root of `rafyr9-png/easytagg-updates`.

For each release:

1. Sign the APK with the permanent EasyTagg release key.
2. Rename the APK to `EasyTagg.apk`.
3. Create a GitHub Release and attach `EasyTagg.apk`.
4. Increase `versionCode` and update `versionName`, `mandatory`, and `releaseNotes` in `version.json`.
5. Commit the updated `version.json` to the `main` branch.

Never publish the signing keystore or its password in this repository.
