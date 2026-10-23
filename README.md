# Form Your Team

Static website hosted on GitHub Pages. The site files are in [`form-your-team/`](./form-your-team/).

## Deployment

The GitHub Actions workflow publishes `form-your-team/` whenever a commit is pushed to `main`. It can also be run manually from the Actions tab.

## Custom domain

The site is prepared for `formyourteam.dk` with a `CNAME` file. Configure the domain's DNS with your domain provider to point it to GitHub Pages; this repository change does not update DNS. Follow GitHub's [custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

The site's canonical and social preview URLs already use `https://formyourteam.dk/`.

## Contact form

The contact form submits through FormSubmit. The first message requires confirming the email sent to the configured inbox. Until confirmed, the form uses its email-app fallback.

## Hosting note

The `_headers` file is retained from the original Netlify package, but GitHub Pages does not apply Netlify-specific headers.
