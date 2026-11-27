# Unofficial certificate-sample webpage

This package displays the image you supplied as an **UNOFFICIAL SAMPLE**. It is not an NPTEL verification page and does not authenticate the certificate.

## Publish free with GitHub Pages

1. Sign in to GitHub or create an account at https://github.com.
2. Create a new **public** repository, for example `certificate-sample`.
3. Upload all files and folders from this package (keep `index.html`, `qr-generator.html`, and the `assets` folder together).
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then click **Save**.
7. Wait a minute or two. GitHub will show your public page URL, usually:
   `https://YOUR-USERNAME.github.io/certificate-sample/`
8. Open `https://YOUR-USERNAME.github.io/certificate-sample/qr-generator.html`.
9. Paste the published page URL from step 7, click **Generate QR code**, then **Download QR PNG**.

## Files

- `index.html` — public sample page with a visible unofficial-sample notice and watermark.
- `assets/certificate-sample.png` — the image you uploaded.
- `qr-generator.html` — makes a QR code after you have the final public URL.

The QR generator loads a small QR library from a CDN, so an internet connection is needed when using it.
