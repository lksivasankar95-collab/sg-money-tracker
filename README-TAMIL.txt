SG Money Tracker APK - Mobile-only build guide

1) Download SG-Money-Tracker-Source.zip.
2) GitHub app or browser: create a NEW PUBLIC or PRIVATE repository named sg-money-tracker. Do not add README/license/gitignore during creation.
3) Open repository > Add file > Upload files. Upload the source ZIP file and commit it to main. The uploaded file must be named exactly: SG-Money-Tracker-Source.zip
4) Add file > Create new file. In filename box enter exactly:
   .github/workflows/android.yml
5) Open the supplied android.yml file, copy all text, paste it into GitHub's editor, then commit the new file to main.
6) Open repository > Actions > Build SG Money Tracker APK. Wait until the run completes successfully (green check).
7) Open the successful workflow run, scroll to Artifacts, tap SG-Money-Tracker-debug-APK to download the artifact ZIP.
8) Extract the downloaded artifact ZIP on your Android phone. Find app-debug.apk and tap it to install. If prompted, allow your browser/file manager to install unknown apps. Only install APKs you built from your own repository.

Important: this workflow builds a DEBUG APK, not a Play Store release. Do not upload private passwords or secrets. APK has not been built/tested yet until the GitHub Actions run succeeds.
