# Manish Kumar — Portfolio

Personal portfolio website: about, resume, projects and contact, in a single static page (HTML, CSS and vanilla JavaScript, no build step).

**Live site:** https://manishkumar-be.github.io/Portfolio/

## Sections
- **About**: summary, highlights, what I do, leadership
- **Resume**: experience (Deloitte US-India, TIET research), education, skills, certifications
- **Projects**: AquaNexus, Thapar Leave Management System, Full-Stack Job Portal, Wheat Growth-Stage Classification, 2D Space Shooter (filterable, with detail pop-ups)
- **Contact**: email, LinkedIn, GitHub and a message form that opens your mail app

## Run locally
Open `index.html` in a browser, or serve the folder:
```bash
python3 -m http.server 8000
```

## Editing
- Text content lives in `index.html`.
- Project cards are generated from the `projects` array at the top of `assets/js/script.js`. Add an object there to add a project.
- Colours and fonts are CSS variables at the top of `assets/css/style.css`.

Layout inspired by the open-source [vCard portfolio](https://github.com/codewithsadee/vcard-personal-portfolio) template (MIT), rebuilt from scratch.
