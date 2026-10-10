---
title: 'Hello, world'
description: 'An example post showing what you can write with Markdown.'
pubDate: '2026-10-08'
---

This is an example post. Every `.md` file in `src/content/blog/` becomes a post at `/blog/<filename>/`, and shows up on the home page automatically, newest first. Copy this file, change the frontmatter at the top, and start writing.

## Code blocks

Code gets syntax highlighting out of the box — just tag the language:

```ts
function greet(name: string): string {
  return `Hello, ${name}!`;
}

console.log(greet('world'));
```

Inline code works too: `npm run dev`.

## Other stuff you'll use

- **Bold**, _italic_, and [links](https://docs.astro.build)
- Lists like this one
- Images: put them in `src/assets/` and reference them like `![alt](../../assets/my-image.png)`

> Blockquotes are nice for callouts or quoting docs.

| Command           | What it does                   |
| ----------------- | ------------------------------ |
| `npm run dev`     | Local preview at localhost:4321 |
| `npm run build`   | Build the site into `dist/`     |
| `git push`        | Publish (GitHub Actions deploys) |

## Drafts

Want to keep a post hidden while you work on it? Keep the file out of `src/content/blog/` until it's ready, or keep it on a separate git branch.
