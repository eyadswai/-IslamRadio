Tanaffas Al-Quran Radio (Android) - how to get the APK
1) Create a free account at github.com, then: + > New repository (name: quran-radio, Public) > Create repository.
2) Click "uploading an existing file", drag ALL files/folders from this folder (including the hidden .github folder), then Commit changes.
   If .github does not upload: Add file > Create new file, name it .github/workflows/build-apk.yml and paste the file contents.
3) Open the Actions tab and wait for "Build Android APK" (about 8-12 minutes). If it does not start: Actions > Build Android APK > Run workflow.
4) When it shows a green check, go to the repository main page and click "Releases" on the right side.
   Download tanaffas-quran-radio.apk from the newest release and install it on your phone.
If the run fails (red X): open it, click the red step, copy the last ~20 lines and send them to Claude.
