# Github-style Alerts for Your Markdown Blog

## What does it do?

You may have the following blockquote (which looks pretty in Typora, Obsidian, etc.):

```markdown
> [!NOTE]
> This is a note.
```

But when rendered to HTML, it's just 2 `<p>` tags inside a `<blockquote>` tag. It should look like this:

> [!NOTE]
> This is a note.

`script.js` can translate the blockquote into an alert!

## Usage

All you need is to reference 3 files in your html:

- `style.css`
- `script.js`
- [`github-markdown-css@5.3.0/github-markdown-dark.css`](https://cdn.jsdelivr.net/npm/github-markdown-css@5.3.0/github-markdown-dark.css)

See [this example](examples/ex0.html).
