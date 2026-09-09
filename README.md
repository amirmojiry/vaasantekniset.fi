# Vaasa Tekniset

Static, bilingual (English/Finnish) website prepared for GitHub Pages.

## Configuration

- Contact email: `sadegh.amirzadeh@vaasantekniset.fi`
- Production domain: `vaasantekniset.fi`
- GitHub repository: `amirmojiry/vaasantekniset.fi`

Review the service descriptions and legal/company wording before publication.

## GitHub Pages

- Repository → Settings → Pages.
- Deploy from the `main` branch, root folder (`/`).
- Add custom domain `vaasantekniset.fi`.
- Enable HTTPS once GitHub makes it available.

## DNS at Hostinger

For the apex domain (`vaasantekniset.fi`) GitHub documents these A records:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

For `www`, use a CNAME pointing to `amirmojiry.github.io`.

GitHub recommends configuring both the apex domain and `www`, and recommends domain verification for security.

## Contact form behavior

This site has no backend. The contact form builds a `mailto:` message and opens the visitor's default email application. No form data is stored by the website.

The Open Application button works the same way and asks applicants to attach their CV manually.
