# Contributing a blog post

This is the PS50 Foundations Year blog. Students publish posts here as part of PS50008A.

Full instructions are on the [How to Publish](https://YOURNAME.github.io/ps50-blog/contributing.html) page of the site. This file is a quick reference.

---

## Quick checklist before opening a pull request

- [ ] My post is in `posts/my-name-short-title/index.qmd`
- [ ] The YAML header has: `title`, `author`, `date` (YYYY-MM-DD), `description`, `categories`, `stream`
- [ ] `quarto preview` runs locally without errors
- [ ] All images are inside `posts/my-name-short-title/images/`
- [ ] I have not edited anyone else's post
- [ ] I have not edited `_quarto.yml`, `custom.scss`, or any site-level files

---

## File structure for your post

```
posts/
  yourname-your-title/
    index.qmd          ← your post
    references.bib     ← citations (if used)
    images/
      cover.jpg        ← cover image (optional)
```

---

## Streams

| Value for `stream:` | What it is |
|---------------------|-----------|
| `homework` | Academic writing, properly cited, structured essay format |
| `publication` | General audience, magazine style, pull quotes, tabsets |
| `signal` | Data/interactivity/video, content-creator mode |

---

## Opening a pull request

1. Fork this repository
2. Clone your fork locally
3. Create your post in `posts/yourname-title/index.qmd`
4. Commit and push to your fork
5. On GitHub, click **Contribute → Open pull request**
6. Title: your post title
7. Description: stream + one-sentence summary + any notes

---

## Questions

Open an [Issue](../../issues) rather than emailing — other students may have the same question.
