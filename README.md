# Vaasa Tekniset

Static, bilingual (English/Finnish) website prepared for GitHub Pages.

## Before publishing

1. Open `app.js`.
2. Replace:

   ```js
   const CONTACT_EMAIL = "your-email@example.com";
   ```

   with the actual email address.

3. Review the service descriptions and legal/company wording before publication.
4. Keep `CNAME` as `vaasatekniset.fi` if the root domain will be used.

## GitHub Pages

- Push these files to a repository.
- Repository → Settings → Pages.
- Deploy from the `main` branch, root folder (`/`).
- Add custom domain `vaasatekniset.fi`.
- Enable HTTPS once GitHub makes it available.

## DNS at Hostinger

For the apex domain (`vaasatekniset.fi`) GitHub currently documents these A records:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

For `www`, use a CNAME pointing to `YOUR_GITHUB_USERNAME.github.io`.

Replace `YOUR_GITHUB_USERNAME` with the account or organization hosting the Pages site.

GitHub recommends configuring both the apex domain and `www`, and recommends domain verification for security.

## Contact form behavior

This site has no backend. The contact form builds a `mailto:` message and opens the visitor's default email application. No form data is stored by the website.

The Open Application button works the same way and asks applicants to attach their CV manually.
