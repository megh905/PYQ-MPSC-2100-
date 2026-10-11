# MPSC PYQ Free

Free mobile-first PWA prototype with:
- Student demo login
- Sample MCQs with answers and explanations
- Subject filter and search
- Bookmarks
- Local Admin Panel to add questions (demo PIN: 2468)
- No payment or subscription section

Important:
- Sample questions are illustrative and are not verified official MPSC PYQs.
- Demo login and admin panel are NOT secure production authentication.
- Questions are saved only in the current browser/device. Other students will not see questions added here.
- The 2,100-question bank and shared online database are not included yet.
- For real student accounts and shared questions, connect Firebase Authentication/Firestore or a secure backend and configure security rules. Never rely on a PIN in client-side JavaScript for real admin access.

Publish:
1. Upload index.html, manifest.json, sw.js, README.md to the root of a GitHub repository.
2. Settings -> Pages -> Deploy from a branch -> main -> /(root) -> Save.
3. Open the published URL. Android Chrome may offer "Add to Home screen" or "Install app".
