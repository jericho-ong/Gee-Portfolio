# Gee Ordoño — Portfolio

A static portfolio website (plain HTML, CSS and a little JavaScript). No build step.

## Structure

```
index.html          the whole site
assets/images/      all photos and work samples (JPEG)
vercel.json         clean URLs and image caching
```

## Preview locally

Open `index.html` in a browser, or run `npx serve .` in this folder.

## Deploy

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
4. Click **Deploy**.

## Editing

- Text lives in `index.html`. Search for the section you want (for example `id="about"`).
- To swap an image, replace the file in `assets/images/` and keep the same file name.
- Contact details are in the `#contact` section.
