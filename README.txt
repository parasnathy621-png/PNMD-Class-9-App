PNMD Class 9 - Auto-Build Ready (v4)

Quick steps to get an APK via GitHub Actions (no local build required):

1. Create a new GitHub repository.
2. Upload the contents of this folder (extract ZIP and commit & push to repo).
3. Push to main branch.
4. In GitHub, open Actions -> 'Android CI - Build APK' workflow run -> download artifact 'pnmd-apk' (app-debug.apk).

Notification setup (optional):
- To enable push notifications, create a Firebase project, add a Web app and copy firebase config to frontend/public/firebase-config.json.
- Add service account to server and install firebase-admin; server sample includes /api/register-token and /api/submit-result endpoints as stubs.

Notes:
- Replace placeholder questions in src/sample_papers.js with NCERT questions if desired.
- For Play Store release, open the Android project in Android Studio and generate a signed bundle.
