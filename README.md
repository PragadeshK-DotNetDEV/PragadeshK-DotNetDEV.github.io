# PragadeshK-DotNetDEV.github.io

Personal portfolio site for Pragadesh Karthick — .NET Software Engineer,
open to .NET / SQL Developer roles. Static HTML/CSS/JS, no build step,
hosted on GitHub Pages.

## Structure

```
.
├── index.html      # single-page site (all content)
├── styles.css      # theme + layout
├── script.js       # mobile nav toggle + footer year
├── favicon.svg     # initials-based favicon
├── resume.pdf      # ADD THIS YOURSELF — linked from the hero "Download Resume" button
├── .nojekyll       # tells GitHub Pages to serve files as-is
└── README.md
```

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```
python -m http.server 8000
```

## Before publishing

- [ ] Save your resume into the repo root as exactly `resume.pdf`
      (rename `PRAGADESH_KARTHICK_Resume_UPDATED.pdf` → `resume.pdf`).

- [ ] Confirm the ObjectTracker tech stack in `index.html` (currently assumed:
      .NET 8, ASP.NET Core, SignalR, Blazor Server, SQL Server).

Content is drawn from the resume. Projects are split into:
- **Professional** — CRMS at IntechHub (proprietary, no repo link) with its
  sub-projects CRMS RESTful API and Pronto UI Application; and Orion Fleet
  Intelligence at K.R.A Systems (proprietary, no repo link).
- **Personal projects** — QueryOptimizer (QueryBench repo) and ObjectTracker.

## Deploy

See the push + GitHub Pages steps provided with the build.
