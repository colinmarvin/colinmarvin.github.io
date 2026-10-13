[README.md](https://github.com/user-attachments/files/33400189/README.md)
# M. Colin Marvin — Academic Website

## File structure

```
index.html           Home page
publications.html    Publications
data-code.html       Data & Code
field-photos.html    Field Photos
media.html           Media
assets/
  css/style.css      All styles
  images/            Drop your photos here
```

## To deploy on GitHub Pages

1. Create a repo named `<your-username>.github.io`
2. Push all files to the `main` branch
3. In the repo Settings → Pages → Source: `main` branch / root
4. Your site will be live at `https://<your-username>.github.io`

## Placeholders to fill in

Search the HTML files for `PLACEHOLDER` comments. Key items:

| File | What to add |
|------|------------|
| `index.html` | Profile photo path, CV PDF path, Google Scholar URL, ORCID URL, Lab Website URL, GitHub URL, bio summary text, research theme text |
| `publications.html` | Nothing — fully populated from CV |
| `data-code.html` | Dataset and code repository entries |
| `field-photos.html` | Image paths for each field location |
| `media.html` | Article URLs for each press mention |

## Adding your photo

Place your headshot at `assets/images/headshot.jpg` (or any name), then in
`index.html` replace the placeholder block with:

```html
<img src="assets/images/headshot.jpg" alt="M. Colin Marvin">
```

## Adding your CV

Place the PDF at `assets/docs/CV_Marvin.pdf`, then update the CV link in
`index.html`:

```html
<a href="assets/docs/CV_Marvin.pdf" target="_blank" rel="noopener">
```
