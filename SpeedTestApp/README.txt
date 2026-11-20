SpeedTest Android App - how to get your APK (free)
===================================================

1. On github.com click "+" > "New repository", name it SpeedTestApp, click "Create repository".

2. Click "uploading an existing file" and drag in from this folder:
     app (folder), build.gradle, settings.gradle, gradle.properties
   Then click "Commit changes".

3. Click "Add file" > "Create new file".
   File name:  .github/workflows/build-apk.yml
   Open build-apk.yml (in this folder) with Notepad, copy everything, paste it in.
   Click "Commit changes".

4. Open the "Actions" tab. Wait for "Build APK" to show a green tick (3-5 min).
   Click it > scroll to "Artifacts" > download "SpeedTest-APK".
   Unzip it to get SpeedTest.apk and install it on your phone.
