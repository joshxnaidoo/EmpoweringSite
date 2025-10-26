Empowering the Nation – Website

A simple, accessible educational website that empowers domestic workers and gardeners with practical skills and learning opportunities.
Developed for Milestone 2 as part of a web and mobile app design project.

✨ Features

Consistent, professional layout (inline CSS)

Easy-to-navigate pages with clear structure

Functional Course Fee Calculator with discounts & VAT

Contact form (demo alert)

Clean typography and card-based design

📂 Folder Structure
EmpoweringSite/
├── index.html          # Home
├── six_month.html      # Six-month learnerships
├── six_week.html       # Six-week short courses
├── calculator.html     # Fee calculator (with JS)
├── about.html          # About page (mission & vision)
├── contact.html        # Contact form
└── README.md           # Project documentation
All pages share the same navigation bar, so the links work as long as files are in the same folder.

🚀 How to Run
Option 1 — VS Code + Live Server (recommended)

Open the folder in VS Code.

Install the Live Server extension (by Ritwick Dey).

Right-click index.html → Open with Live Server.

Your browser opens automatically — navigate using the menu.

Option 2 — Browser

Double-click index.html to open it in your default browser.

🧮 Calculator Logic

Six-month courses: First Aid, Sewing, Landscaping, Life Skills = R1500 each

Six-week courses: Child Minding, Cooking, Garden Maintenance = R750 each

Discounts

2 courses = 5 %

3 courses = 10 %

4 or more courses = 15 %

VAT 15 % added after discount

Displays a full quotation breakdown: subtotal → discount → VAT → total

🌐 Publish with GitHub Pages

Push this project to your GitHub repository.

Go to Settings → Pages.

Under Build and deployment, choose Deploy from branch → main.

Click Save.

After a minute, your live site appears at:https://<joshxnaidoo>.github.io/EmpoweringSite/

🤝 Team Collaboration

Clone the repo
git clone https://github.com/<your-username>/EmpoweringSite.git
cd EmpoweringSite

Create a branch
git checkout -b feature/update-homepage

Commit and push
git add .
git commit -m "Updated homepage layout"
git push -u origin feature/update-homepage

Open a Pull Request
On GitHub → Compare & Pull Request → Request review.

🧰 Troubleshooting

Push rejected / fetch first
git fetch origin
git pull --rebase origin main
git push -u origin main

Overwrite remote (if necessary)
git push -u origin main --force

Links not working

Verify filenames match exactly:

index.html, six_month.html, six_week.html, calculator.html, about.html, contact.html

Keep all files in one folder.

Browser not updating

Save (Ctrl/Cmd + S) and hard-refresh:

Windows → Ctrl + F5

Mac → Cmd + Shift + R

📝 Notes

Inline CSS follows the same structure as the provided wireframes.

Layout uses centered header, clean navigation, and grid-based cards.

Ideal for demonstration and training purposes.

👩🏽‍💻 Credits

Developed by Precious Radebe & Team
Project: Empowering the Nation
Module: Milestone 2 – Web and Mobile Design

📜 License
MIT License
Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction...



