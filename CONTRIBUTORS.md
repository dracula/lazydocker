# 🤝🏻 Contributors

> "We learn big things from small experiences" - **Bram Stoker**

Dracula Theme is an open-source project driven by and for the community. Most apps that support the theme are contributions from our community.

As much as the team is responsible for the core theme and wants to support all available applications, we can only do so much ourselves.

That's why the community is essential for this project to keep evolving. Below are some tips for contributors.

## 🎃 Recommendations

- [`config/dracula.yml`](config/dracula.yml): Lazydocker's Dracula theme settings.
- [`README.md`](README.md): Introduction for GitHub users.
- [`INSTALL.md`](INSTALL.md): Installation instructions.
- [`screenshot.png`](screenshot.png): A real capture of the theme running in lazydocker.

Keep the palette consistent with Dracula and check changes in lazydocker before submitting a pull request.

Previously, default formatting settings were included. Now, we recommend preparing your theme with this command:

```bash
npx prettier . --write
```

> What is that `npx` thing? `npx` ships with `npm` and lets you run locally installed tools.

## 🦉 The Dracula Theme Team

The creators behind the scenes are [Lucas de França](https://github.com/luxonauta) and [Zeno Rocha](https://github.com/zenorocha).

Reach out via [email](mailto:support@draculatheme.com) or follow us on Twitter/X: [Zeno Rocha](https://twitter.com/zenorocha) and [Luxonauta (Lucas)](https://twitter.com/luxonauta).

## 🌐 How the website gets updated

Theme pages on [draculatheme.com](https://draculatheme.com) are generated at build time from the files in each theme repository (`README.md`, `INSTALL.md`, and screenshots). The website doesn't fetch this content live.

This means a merged pull request won't show up on the website right away; it appears after the next site rebuild. Rebuilds happen roughly once a week, usually in batches alongside other theme updates and maintenance fixes.

If your change needs to go live sooner, mention our team in the pull request and we may trigger a rebuild manually.
