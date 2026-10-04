# Build Lumo Edge Forest APK from an Android phone

This project includes a GitHub Actions workflow that builds a debug APK in the cloud.

## Phone-only steps
1. Create/sign in to GitHub.
2. Create a new repository (for example: `LumoEdgeForest`).
3. Upload all files in this project into the repository root.
4. Open the repository's **Actions** tab.
5. Select **Build Lumo Edge APK**.
6. Tap **Run workflow** (or push to `main`/`master` to trigger it).
7. Wait for the green check mark.
8. Open the completed workflow run and scroll to **Artifacts**.
9. Download `LumoEdge-Forest-debug-APK`.
10. Extract the downloaded ZIP and install `app-debug.apk` on Android.

## Important
The current app is a dashboard/demo scanner. It does **not** yet have a real live market-data feed and it does **not** connect to Exness or place trades automatically. Live scanning requires a market-data source/API to be integrated.
