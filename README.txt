Phoenix share-card package

Goal:
Create a share link that shows a preview card image in Telegram / LINE / Facebook.
When people tap the card, it redirects to the Google Sites sale page.

Files:
- index.html
- preview-card.jpg: link preview image, 1200x630
- preview-original.jpg: original poster image, shown on the redirect page

Destination sale page:
https://sites.google.com/view/phoenix-medical-aesthetic/%E0%B8%AB%E0%B8%99%E0%B8%B2%E0%B9%81%E0%B8%A3%E0%B8%81

How to use:
1. Upload this whole folder to Netlify, Vercel, GitHub Pages, or another static host.
2. After publishing, copy the new public URL.
3. Send only that new URL in Telegram / LINE.

Important:
Google Sites itself cannot reliably force this preview image. The preview card will come from this hosted share page, not from the original Google Sites URL.

If a platform does not show the new image immediately:
- Telegram / Facebook / LINE may cache previews.
- Change the share URL path slightly, or use the platform's sharing debugger/cache refresh tool.
