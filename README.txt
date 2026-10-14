DHANUSH GUBALA - 3D PORTFOLIO  (final build, performance-tuned)
============================================

HOW TO RUN (2 steps)
1. Unzip this folder (keep all files together).
2. Double-click index.html  (Google Chrome or Microsoft Edge recommended).
   It works offline. Everything it needs is in this folder.

If a browser blocks anything, use a tiny local server instead:
   Open a terminal in this folder and run:   python -m http.server 8000
   Then open http://localhost:8000

FILES
  index.html            the website
  three.min.js          3D engine (bundled, no internet needed)
  covers.js             project cover images
  resume.pdf            your resume (the Resume card downloads this)
  og-image.jpg          preview image shown when the link is shared (WhatsApp, LinkedIn, etc.)
  favicon.svg, apple-touch-icon.png, icon-192.png, icon-512.png, manifest.webmanifest   icons
  robots.txt, sitemap.xml                                                                search engines

PUT IT ONLINE FOR FREE (GitHub Pages)
1. Open your GitHub repository for the portfolio (github.com/dhanush-g7/Dhanush-Portfolio).
2. Upload ALL files from this folder to the repository root (replace the old ones).
3. Settings > Pages > deploy from the main branch.
Your site will be at  https://dhanush-g7.github.io/Dhanush-Portfolio/
If you use a different address, replace  https://dhanush-g7.github.io/Dhanush-Portfolio/
inside index.html, robots.txt and sitemap.xml (search for it with Ctrl+F).
Also works on Netlify: drag and drop this folder at app.netlify.com/drop

AFTER IT IS ONLINE (recommended, 5 minutes)
- Open https://search.google.com/search-console, add your site and submit sitemap.xml
- Test the share preview: paste your link in WhatsApp or LinkedIn.
- Re-run Lighthouse: open the site in Chrome > F12 > Lighthouse > Analyze.

WHAT YOU CAN EDIT  (index.html, near the top of the main script: "EDIT YOUR DETAILS HERE")
- email, skills, projects (title, description, link)
- social: add whatsapp (number with country code), linkedin, instagram links
- timeline = the 4 journey signs near the start
- testimonials = the 3 rooftop review signs (replace with real client reviews)
To change your resume, replace resume.pdf with a new file of the same name.

CONTROLS
- Scroll / swipe up and down = fly forward
- Drag (mouse) or swipe sideways (phone) = look around 360 degrees
- Top-right buttons: time of day, rain, quality (Low / Medium / High), language (English / Telugu)
- Tap robots, cars, billboards, the Resume card and the Contact button
- Keyboard: Tab to the buttons, Enter or Space to press them
