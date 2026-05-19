# GTS Picture Compressor

This app can run three ways:

1. **Online** via Netlify
2. **Online** via GitHub Pages
3. **Locally with no domain required**

## Recommended web hosting

Use Netlify and point it at this repo.

- Build command: leave blank
- Publish directory: `.`
- The included `netlify.toml` already tells Netlify to publish the repo root

## Recommended if web filters block the site

1. On GitHub, click **Code > Download ZIP**
2. Extract the ZIP to your computer
3. Open `index.html` in **Chrome** or **Microsoft Edge**
4. Choose files or a folder
5. Click **Compress to 100 KB per image**

## Why local mode helps

- avoids GitHub Pages reputation blocks
- keeps files on the local machine
- works without needing a custom domain
- handles large batches more safely by processing one file at a time

## Notes

- HEIC and HEIF files are converted to JPG first, then compressed
- Chrome and Edge give the best results for large batches because they can stream the ZIP directly to disk
- Other browsers still work, but very large batches may use more memory during the final ZIP download step
