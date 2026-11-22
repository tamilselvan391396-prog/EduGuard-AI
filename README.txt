AI CLASS MONITOR — INSTALLABLE ANDROID WEBSITE (PWA)

PUBLISH TO GITHUB PAGES
1. Extract this ZIP on your Android phone.
2. In your GitHub repository, upload/replace index.html, manifest.webmanifest and sw.js in the repository root.
3. Upload the entire icons folder, including icon-192.png and icon-512.png.
4. Commit the changes to the main branch.
5. In repository Settings > Pages, publish from main / (root).
6. Open the HTTPS GitHub Pages address in Chrome.

INSTALL ON ANDROID
1. Open the published HTTPS website in Chrome.
2. If an "Install on this phone" button appears, tap it and confirm Install.
3. If the button does not appear, open Chrome's three-dot menu (⋮) and choose "Install app" or "Add to Home screen".
4. Find AI Class Monitor on your home screen and open it.

FEATURES
- Monitoring screen opens first.
- Start Monitoring requests microphone permission.
- Browser speech recognition plus sustained microphone loudness triggers a photo attempt after more than 5 seconds.
- Camera is requested only at capture time.
- Photos are stored in this website's local IndexedDB storage on this phone.
- Gallery has a passkey authentication gate.
- Export photo backup downloads copies.

LIMITATIONS / PRIVACY
- This is an experimental prototype, not a reliable trained sound classifier. It may miss or misclassify speech and cannot reliably distinguish shouting from ordinary talking.
- Android may offer fingerprint, face, or device PIN/pattern for passkey verification; websites cannot force fingerprint-only.
- Passkey is a UI access gate, not encryption of photo files.
- Photos are stored in browser website storage, not automatically in the phone's regular Gallery/DCIM folder.
- Clearing browser site data may erase photos.
- Camera/microphone require HTTPS and permission. Keep the app in the foreground; screen locking/backgrounding may suspend monitoring.
- Obtain school approval and inform students/parents as required before recording.
