<!-- 2023/05/16 MkDocs 1.4.3 -->

## GitHubPages-MkDocs

**MkDocs with GitHub Pages via GitHub Actions (minimal configuration)**

- [GitHub Pages](https://pages.github.com/)
- [MkDocs](https://www.mkdocs.org/)

MkDocs has a `mkdocs gh-deploy` command, but using this method you can publish the original source to the repository instead of the built HTML. You commit instead of the MkDocs command.

## How to use

1. Edit `mkdocs.yml` and `docs/index.md`, add more files if needed.
2. Add the pip package to `requirements.txt` . (Themes and plugins)
3. Commit to a Git project: `git push`
4. Select **Setting - Pages** from the GitHub project, Select **GitHub Actions** for "Source".
5. Set "Custom domain" if necessary. (Note: `CNAME` file does not work with GitHub Actions)

## Build error

Many of the build error are that you mistyped `mkdocs.yml`
or you forgot to add the package to` requirements.txt`.
Check the file change immediately before the error occurred.

This is often not a problem with this project.
You should not open an issue for that.

## Fork of this project

If you fork this project, be sure to change something and commit.
If you re-deploy without changing anything, it's my commit and I'll be notified.
