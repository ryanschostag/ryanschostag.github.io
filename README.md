[Home](./) | [About](about.md) | [Projects](projects.md)

<p align="center">
  <img src="assets/images/logo.png" alt="Logo" width="140"/>
</p>

<h1 align="center">Ryan Schostag — Python & Data Engineering Consulting</h1>

---

## 🔗 Live Portfolio

**https://ryanschostag.github.io**

This site is a direct-outreach landing page for short-term technical consulting. It explains how I help businesses with:

- Broken or unreliable data pipelines
- Python and SQL troubleshooting
- Data cleanup and migration
- Repetitive reporting and data-work automation
- API integrations and testing

Pages are written in Markdown with a small custom Sass layer and served through GitHub Pages using the Cayman theme. The site uses a mailto CTA rather than a backend form or paid third-party service.

---

## 📂 Repository Structure

```
├── index.md # Home page
├── about.md # About Me page
├── projects.md # Case studies & examples
├── _config.yml # GitHub Pages configuration
└── assets/
  ├── css/
  │   └── style.scss # Custom responsive theme styling
    └── images/
        └── logo.png # Portfolio logo
```

## Verify Before Publishing

1. Work on a feature branch such as `dev` and review the rendered page at desktop and mobile widths.
2. Check every navigation link, the service pricing language, FAQ disclosures, and each `mailto:` CTA.
3. Run `git diff --check` to catch whitespace errors.
4. Build the site locally with `bundle exec jekyll build` when Ruby, Bundler, and Jekyll are installed. The generated `_site/` directory should build without errors.
5. Push the branch and open a pull request into `main`. Review the changed files and use the pull request's GitHub Pages preview, if enabled.
6. After merging, open `https://ryanschostag.github.io` in a private browser window and test the live links and email CTA.

GitHub Pages performs the authoritative deployment build. If the local Jekyll command is unavailable, install Ruby and Bundler first or rely on the pull request/deployment build status before merging.

---

## Technologies Highlighted

- **Python, FastAPI, SQL**
- **Azure (ADF, Synapse, Blob Storage)**
- **Databricks / Spark / Delta Lake**
- **GitHub Actions & CI/CD**
- **Docker & containerization**
- **ETL/ELT architecture & automation**
- **pytest, data quality, and regression testing**

---

## 📬 Contact

For a technical consultation or fixed-scope project:

- **Email:** ryan.schostag@gmail.com  
- **LinkedIn:** https://linkedin.com/in/ryanschostag  
- **GitHub:** https://github.com/ryanschostag  

---

## 📄 License

This repository contains the site source for GitHub Pages.
