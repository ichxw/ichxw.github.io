# Posts and Images Organization

Use this structure for new blog posts:

- Markdown posts go in `_posts/`
- Images for each post go in `assets/images/posts/<post-slug>/`

## Recommended pattern

If your post file is:

`_posts/2026-04-13-my-post-title.md`

then put images in:

`assets/images/posts/my-post-title/`

Example:

- `_posts/2026-04-13-my-post-title.md`
- `assets/images/posts/my-post-title/figure1.png`
- `assets/images/posts/my-post-title/figure2.jpg`

## Referencing images in markdown

Use root-relative paths in posts:

```md
![Figure caption](/assets/images/posts/my-post-title/figure1.png)
```

For controlled sizing:

```html
<img src="/assets/images/posts/my-post-title/figure1.png" alt="Figure caption" width="700" />
```

## Why this layout

- keeps each post self-organized
- avoids dumping all images into one folder
- makes future edits and cleanup easier
- works well with Jekyll and GitHub Pages
