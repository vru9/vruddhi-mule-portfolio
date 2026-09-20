# Vruddhi Mule — Portfolio

A responsive personal portfolio for Vruddhi Mule, an Artificial Intelligence and Data Science undergraduate in Mumbai.

**Live website:** [small-snowflake-1c3e.mule-v.workers.dev](https://small-snowflake-1c3e.mule-v.workers.dev/)

## About

The portfolio includes an introduction, four selected projects, internship experience, education, technical skills, achievements, and contact links. Visitors can also download the resume.

Built with HTML, CSS, and vanilla JavaScript. No package installation or build step is required.

## Run locally

From the repository directory, run:

```sh
python3 -m http.server 4173 --bind 127.0.0.1 --directory dist
```

Open <http://127.0.0.1:4173> in your browser.

## Files

```text
dist/
├── index.html                    # Portfolio content and page structure
├── styles.css                    # Theme and responsive layouts
├── script.js                     # Mobile navigation
└── assets/
    ├── vruddhi-mule.jpeg          # Portrait
    └── vruddhi-mule-resume.pdf    # Downloadable resume
```

## Update and deploy

Edit the files in `dist/` and reload the local preview to review your changes. The contents of `dist/` are ready to upload to a static website host, with `index.html` at the upload root.

The current public website is hosted on Cloudflare Workers. Pushing to this repository does not automatically update that deployment; upload the updated website files through the existing Cloudflare project unless Git integration is configured separately.

## Contact

- [LinkedIn](https://www.linkedin.com/in/vruddhi-mule-4a65612b5/)
- [GitHub](https://github.com/vru9)
- [Email](mailto:vruddhimule@gmail.com)
