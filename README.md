# PS51009D Science Communication Blog

Student blog for **PS51009D Applications of Psychological Research**, Goldsmiths, University of London.

Live site: **https://LittleMonkeyLab.github.io/ps51009d-blog**

---

## For students

Read the full publishing guide at: `https://LittleMonkeyLab.github.io/ps51009d-blog/contributing.html`

Quick summary:
1. Fork this repo
2. Copy a template from the repo root (`_template-mvp.qmd` for a clean start, or `_template-full.qmd` to see all available features)
3. Put it in `posts/yourname-topic/index.qmd`
4. Write your post
5. Open a pull request

Publishing on the blog is optional — assessment submissions go via **Moodle**. See the Assessment page for the submission link.

---

## For the module convenor

### Initial setup

1. Create a new GitHub repo and push this project to it
2. In repo Settings → Pages → Source: set to **GitHub Actions**
3. Update all `YOURNAME` placeholders in `_quarto.yml`, `contributing.qmd`, `README.md`, and `about.qmd`
4. Push to `main` — the Actions workflow will build and deploy automatically

### Reviewing student pull requests

- The Actions workflow runs on every PR — check the build passes before merging
- PRs from forks will have limited Actions access by default; you may need to approve the workflow run manually the first time
- To reject a post: close the PR with a comment explaining what needs to change

### Local preview

```bash
quarto preview
```

### Render to `docs/`

```bash
quarto render
```

---

## Tech stack

- [Quarto](https://quarto.org) — publishing system
- [Hypothesis](https://web.hypothes.is) — annotation / comments
- GitHub Pages — hosting
- GitHub Actions — CI/CD

---

## Licence

Module materials: Gordon Wright, Goldsmiths, University of London.
Student posts: CC BY 4.0 (per post, by respective authors).
