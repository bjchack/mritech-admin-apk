MR ITECH ADMIN - ANDROID WEBVIEW APP PROJECT

App name: Mr Itech Admin
Start URL: http://mritech.online/website_admin/index.php?p=

Features:
- Opens the admin website on launch
- JavaScript and DOM storage enabled
- Top loading progress indicator
- Android Back button navigates WebView history
- Custom launcher icon

BUILD APK WITHOUT A PC (using GitHub Actions):
1. Create a free GitHub account and a new repository.
2. Upload the CONTENTS of this folder (including the hidden .github folder) to the repository's main branch.
3. Open the repository's Actions tab and select "Build Mr Itech Admin APK".
4. Tap "Run workflow" if it has not started automatically.
5. When the run finishes successfully, open the run, scroll to Artifacts, and download "Mr-Itech-Admin-APK".
6. Extract the downloaded artifact ZIP. Install app-debug.apk on your Android phone. Android may ask you to allow installs from that browser/file manager.

The workflow builds a DEBUG APK for testing. It is not a Play Store release build.

SECURITY NOTE:
The supplied URL uses HTTP, not HTTPS. Admin login credentials are safer after the website is migrated to HTTPS.

This ZIP is Android source plus a cloud build workflow; it is NOT itself an APK.
