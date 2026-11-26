AI Clip Studio — Play Store preparation kit

This package contains the existing mobile HTML app wrapped with basic PWA metadata. It is NOT a signed Android App Bundle (.aab) yet.

Included: index.html, manifest.json, service-worker.js, icon.svg.

Next steps to publish on Google Play:
1. Test the HTML app on Android and review every feature; ensure no broken/inert buttons and no misleading AI/API claims.
2. Create a Google Play Console developer account and complete identity verification. Registration fee: US$25 one-time (Google's current published requirement).
3. Wrap this web app into Android using Capacitor (requires Node.js and Android Studio on a computer):
   - Create a Capacitor app, copy this folder's web assets into its web directory.
   - Add Android platform, configure application ID (e.g. com.yourname.aiclipstudio), app name, icon and splash screen.
   - Open in Android Studio, test on devices, build a signed Android App Bundle (.aab).
4. Upload AAB to Play Console internal testing. For new personal accounts, Google currently requires a closed test with 12 testers continuously opted in for 14 days before applying for production access.
5. Complete Play listing: app description, screenshots, 512x512 icon, feature graphic 1024x500, privacy policy URL, Data safety, content rating, ads declaration, app access instructions.
6. Apply for production access, submit for review.

Privacy: Before publishing, inspect the app for local storage, file handling, external calls and data collection. Create an accurate privacy policy and Data safety declaration.
