# BPCL Loyalty App

![BPCL Loyalty App](BPCL/img/preview.png)

Status: Ready for design polish and documentation

A loyalty management web application for BPCL including:
- Admin Dashboard
- Dealer Panel
- Customer Registration & Login
- Reward Points & Purchase History

Built using HTML, CSS, and JavaScript (static UI prototype).

Badges
- Build / CI: none yet
- License: [LICENSE](LICENSE)

Quick demo
- Open BPCL/splash.html in a browser (or enable GitHub Pages and visit the project's Pages site).
- Or open any of the panel pages in the `BPCL/` folder (admin_dashboard.html, dealer_dashboard.html, dealer_register.html, etc.)

Why this repository
- Static UI prototype for a loyalty app used to design flows for Admin, Dealers, and Customers.
- Good starting point to wire to a backend or convert into a full-stack app.

Repository layout
- BPCL/ — the existing UI: HTML, CSS and img assets.
  - BPCL/splash.html — landing / splash
  - BPCL/style.css, dealer_style.css, admin_profile.css, etc.
  - BPCL/img/ — images and screenshots
- docs/ — (added) a lightweight project landing page suitable for GitHub Pages
- .github/ — community files (issue & PR templates)
- README.md, CONTRIBUTING.md, CODE_OF_CONDUCT.md, LICENSE

Screenshots and media
- Add screenshots to `BPCL/img/` (e.g. `BPCL/img/preview.png`, `BPCL/img/admin-dashboard.png`) and reference them in the README.
- For animated walkthroughs add a `BPCL/demo.gif`.

How to run locally
- This project is static HTML/CSS/JS — open the HTML files directly in a browser.
- For a local dev server, run (Python 3):
  - python -m http.server 8000
  - then open http://localhost:8000/BPCL/splash.html

Suggested next steps (pick one)
1. Polish styles: unify with a single stylesheet or a framework (Bootstrap/Tailwind).
2. Reorganize assets into `BPCL/assets/{css,js,img}` and update HTML paths.
3. Add a small Node/Express or Flask backend to serve data and demonstrate registration/login.
4. Enable GitHub Pages from `docs/` to show the demo online.

Contributing
Please read CONTRIBUTING.md for contribution guidelines and the PR template.

License
This project is distributed under the license in the LICENSE file.
