# Deploying LivLit

Upload everything in this folder to your host (GitHub Pages, Netlify, Firebase Hosting). `index.html` is the app. Keep `support.js`, `manifest.json` and the two icon files next to it.

## Lock the data to the two of you (do this once)
1. Firebase console, Authentication, Sign-in method: turn on Email/Password.
2. Authentication, Users: add one user for Litch and one for Liv.
3. Firestore Database, Rules: paste the contents of `firestore.rules`, put both emails in, and Publish.
4. Open the app. When the rules are on, it asks each of you to sign in once per device.

Until step 3 is published, the app works without signing in.

## Add to your phone
Open the site in Safari, Share, Add to Home Screen.
