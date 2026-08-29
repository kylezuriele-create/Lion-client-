# Scythei Client — GitHub APK Build

## Upload
1. Create a GitHub repository.
2. Upload the contents of this folder.
3. Commit/push to `main` (or `master`).

## Build
Open the repository's **Actions** tab and select **Build Scythei Client APK**.
Press **Run workflow**.

When the build finishes:
**Actions → completed workflow → Artifacts → Scythei-Client-debug**

The downloaded artifact contains the debug APK.

## Notes
- This is a debug APK for testing.
- The launcher starts the installed Minecraft Bedrock app using its normal Android launch intent.
- It does not modify Minecraft's protected game code.
