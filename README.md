# Godfrey Glory — portfolio

A responsive, static portfolio for highlighting my hands-on Cloud, DevOps, SRE, CI/CD, and DevSecOps projects.

## Preview locally

Open `index.html` in a browser, or start a simple local server:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

This site includes a GitHub Actions workflow at `.github/workflows/pages.yml`.

1. Push these files to the `main` branch of a public repository.
2. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source.
3. Open **Actions** and confirm that the **Deploy portfolio to GitHub Pages** workflow completes.

For the current repository name `my-website`, the Pages address will be `https://uyigodfrey.github.io/my-website/` after Pages is enabled and the workflow succeeds.

## Personalize before sharing

- Add a professional email or LinkedIn URL if you want recruiters to reach you outside GitHub.
- Keep the project descriptions aligned with the repository READMEs and what you have actually run.
- The featured project links currently point to public repositories under `UyiGodfrey`.

## Built with

HTML, CSS, and vanilla JavaScript. No build step or third-party JavaScript dependencies.
