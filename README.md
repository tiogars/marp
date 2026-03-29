# Marp Presentation Template

![Deploy to GitHub Pages](https://github.com/tiogars/marp/actions/workflows/deploy-slides.yml/badge.svg)

**View the latest slides:** [GitHub Pages - HTML Slide Deck](https://tiogars.github.io/marp/)

This repository provides a simple template to help you get started with [Marp](https://marp.app/), the Markdown Presentation Ecosystem.

## About Marp

Marp allows you to create beautiful slide decks using Markdown. It supports live preview, custom themes, and export to PDF, PPTX, HTML, and image formats.

## How to Use This Template

1. **Install Marp CLI** (if you haven't already):

```sh
npm install -g @marp-team/marp-cli
```

1. **Write your slides** in Markdown files (e.g., `presentation/index.md`).

1. **Preview and export** your slides using Marp CLI or the [Marp for VS Code extension](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode).

## Automatic Deployment to GitHub Pages

This repository uses GitHub Actions to automatically build and publish the HTML slide deck to GitHub Pages on every push to the `main` branch.

- The workflow is defined in `.github/workflows/deploy-slides.yml`.
- The generated HTML is published from the `presentation/` folder to the `gh-pages` branch.
- The slides are available at: [https://tiogars.github.io/marp/](https://tiogars.github.io/marp/)

No manual action is required—just push your changes to `main`!

## Resources

- [Marp Official Website](https://marp.app/)
- [Marp Documentation](https://marp.app/docs/)
- [Marp GitHub](https://github.com/marp-team/marp)

---

> This project is a starting point for creating your own Marp-based presentations. Customize the `presentation/` folder and enjoy writing slides in Markdown!
