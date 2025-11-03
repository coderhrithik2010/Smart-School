
Smart Classroom — Ready-to-upload site (Modern UI)
Files included:
- index.html  -> Home page (QR instructions + open class)
- teacher.html -> Teacher panel to add students, enter marks, submit complaints
- dashboard.html -> Principal view: pick class, see marks chart, view all complaints
- style.css -> styling for modern blue UI

How to use:
1. In Firebase console, make sure Realtime Database is created (test mode allowed while building).
2. The Firebase config is already embedded in files (the config you provided).
3. Upload all files to a GitHub repository (main branch). In repo settings -> Pages -> Deploy from main branch.
4. Open the published URL and add ?class=class9A (or visit teacher.html?class=class9A) to work with a specific class.
5. Generate QR codes using the published link + ?class=class9A, e.g. https://yourusername.github.io/smart-classroom/?class=class9A
