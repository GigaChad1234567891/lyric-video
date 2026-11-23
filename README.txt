LYRIC VIDEO - BUILD THE ANDROID APP IN THE CLOUD (no Android Studio needed)

1. Make a free account at github.com and click New repository. Name it lyric-video.
2. Click "uploading an existing file", then drag EVERYTHING from this folder into
   the page (package.json, capacitor.config.json, the www folder and the .github folder).
   Click Commit changes.
3. If the .github folder did not upload: click Add file > Create new file, type the
   name   .github/workflows/build.yml   and paste in the contents of build.yml from this zip.
4. Open the Actions tab. Wait 3 to 6 minutes for "Build APK" to finish (green tick).
5. Click the finished run, scroll to Artifacts, download "lyric-video-apk".
6. Unzip it and send app-debug.apk to your phone.
7. On the phone, open the file and allow "Install unknown apps" if it asks.

Notes
- This is a debug build, which is fine for your own phone.
- The Record button does not work in the Android app. Use your phone's screen recorder.
- To update the app, replace www/index.html in your repository and the build runs again.
