# Fatemeh Faryabi — personal site

Static pixel-style site: resume, blog and workshops.

- Home: `index.html` → `/`
- Resume: `resume/index.html` → `/resume/`
- Blog: `blog/index.html` → `/blog/`
- Workshops: `workshops/index.html` → `/workshops/`

## Deploy

Every push to `main` deploys automatically to the host via FTP
(see `.github/workflows/deploy.yml`).

Required GitHub Secrets (Settings → Secrets and variables → Actions):
- `FTP_SERVER` — e.g. `brainping.me` or the host IP
- `FTP_USERNAME` — FTP / DirectAdmin username
- `FTP_PASSWORD` — FTP / DirectAdmin password
