# वो एक जवाब — GitHub Pages Website

This folder contains a mobile-friendly public comic website.

## Files
- `index.html` — website homepage and embedded PDF reader
- `vo-ek-jawab-comic.pdf` — comic PDF (21 pages)
- `cover-preview.jpg` — cover preview image

## Publish with GitHub Pages
1. Sign in to GitHub and create a **Public** repository (for example `vo-ek-jawab`).
2. Upload all three files from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for GitHub Pages to publish. Your public site URL will look like:
   `https://YOUR-USERNAME.github.io/vo-ek-jawab/`

## Notes
- The PDF is public because the repository and website are public.
- The website embeds the PDF. Some mobile browsers may open the PDF in a separate viewer; the download and new-tab links are provided as alternatives.
- If the chapter starting pages change in a future PDF, update the page numbers in the `chapters` array in `index.html`.
