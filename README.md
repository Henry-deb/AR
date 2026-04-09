DecoHub AR Project

Welcome to DecoHub AR — a lightweight, web-based AR project for visualizing event décor ideas! No heavy software like Unity required — everything runs in the browser.# AR
DECOHUB AN AR SYSTEM

Project Structure
decohub/
├─ index.html          # Main landing page
├─ ar-view.html        # AR view page
├─ css/
│  └─ styles.css       # Styling for the web pages
├─ js/
│  └─ main.js          # Main JavaScript logic
├─ assets/
│  └─ models/          # 3D models for AR
⚡ Getting Started
1. Clone the repo
git clone git@github.com:Henry-deb/AR.git
cd AR
2. Install dependencies

No installation needed — everything runs in your browser.
Just open index.html or ar-view.html in Chrome, Firefox, or Edge.

3. Workflow for teammates
a) Pull latest changes before working:
git pull origin main
b) Make your changes
Add/modify JS in js/main.js
Update HTML pages (index.html, ar-view.html)
Add new 3D assets to assets/models/
Update styles in css/styles.css
c) Stage and commit your changes
git add .
git commit -m "Describe what you did"
d) Push your changes
git push origin main
4. Notes
Keep file structure intact — especially assets/models/
Avoid conflicts by always pulling latest changes before starting work
If conflicts happen, Git will guide you to merge them
5. Browser Testing
Open index.html in your browser
Click through your UI and test AR features via ar-view.html
Use simple local server if needed:
# Using Python 3
python -m http.server
# Open browser at http://localhost:8000
6. Helpful Git Commands
Task	Command
Check status	git status
See commits	git log --oneline
Pull latest changes	git pull origin main
Stage files	git add <file>
Commit staged files	git commit -m "message"
Push changes	git push origin main
Clone repo	git clone git@github.com:Henry-deb/AR.git
