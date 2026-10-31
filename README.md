# Hacktoberfest 2026

A welcoming open-source landing page for Hacktoberfest 2026, built with plain HTML and CSS. The goal of this project is to help contributors practice Git, GitHub workflows, and web accessibility improvements in a friendly, beginner-friendly environment.

## Project goals

- Showcase a clean community landing page for Hacktoberfest 2026
- Make it easy for contributors to improve design, content, and accessibility
- Keep the project beginner-friendly and easy to run locally
- Encourage open-source participation with small, approachable contributions

## Local development

You can open `index.html` directly in a browser, or run a local server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Hacktoberfest contribution guide

We welcome contributions from all skill levels. Whether you are brand new to open source or looking to improve your frontend and GitHub workflow, this project is a great place to start.

### Good ways to contribute

- Improve mobile responsiveness
- Fix accessibility issues
- Refine layout spacing and typography
- Add better semantic HTML
- Improve page copy and event details
- Add sections for community highlights or sponsor links
- Improve the visual hierarchy and readability of the landing page

### Contribution workflow

1. Fork the repository
2. Create a feature branch for your work
3. Make your changes and test them locally
4. Open a pull request with a clear summary
5. Reference the relevant issue if applicable

### Before you start

- Keep changes small and focused
- Follow the existing design language of the project
- Prefer simple, maintainable HTML and CSS
- Check that your edits still work on common screen sizes
- Avoid unnecessary dependencies or build tooling for this static page

## Beginner-friendly issue ideas

These are examples of issues that are simple, beginner-accessible, and valuable for the project:

- Add a responsive mobile nav or simplify the current nav layout
- Improve keyboard focus styling for links and buttons
- Add a "Why contribute" or "Community values" section to the page
- Update event information cards with clearer labels and consistent spacing
- Make the project cards more visually balanced and easier to scan
- Add alt text or better semantic labeling where needed
- Improve color contrast for readability and accessibility
- Add a dedicated "How to participate" section for Hacktoberfest contributors
- Improve the hero section layout for smaller screens
- Add a footer section with community links or repository information

## Community standards

We aim to keep this project welcoming, respectful, and constructive. Please review the project guidelines in [CONTRIBUTING.md](CONTRIBUTING.md) and the [Code of Conduct](CODE_OF_CONDUCT.md) before contributing.

## Deployment

GitHub Actions deploys the static site to GitHub Pages whenever changes are pushed to `main`. To enable the first deployment, open the repository's **Settings → Pages** and set the build and deployment source to **GitHub Actions**. The workflow publishes the repository's root files without a build step.

After the workflow completes, the site is available at [https://basebuild17.github.io/Hacktoberfest-2026/](https://basebuild17.github.io/Hacktoberfest-2026/). You can also start a deployment manually from the **Actions** tab using **Deploy to GitHub Pages**.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for the contribution guidelines.

## License

This project is licensed under the MIT license. See [LICENSE](LICENSE) for details.
