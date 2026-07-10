Phoenix share-card package

Goal:
Create a share link that shows a preview card image in Telegram / LINE / Facebook.
When people tap the card, it redirects to the Google Sites sale page.

Files:
- index.html
- preview-card.jpg: link preview image, 1200x630
- preview-original.jpg: original poster image, shown on the redirect page

Current destination:
https://docs.google.com/forms/d/e/1FAIpQLSfLuhHCUuCGnI8DkSsVKUYDNq8meUH0xNBwy-fSqv5f7WOwQQ/viewform

Note:
The DRIP VITAMIN Google Site was still unpublished when this package was updated.
Use the Google Form as the temporary redirect target. After publishing the Google
Site sales page, update the redirect URL in index.html.

How to use:
1. Upload this whole folder to Netlify, Vercel, GitHub Pages, or another static host.
2. After publishing, copy the new public URL.
3. Send only that new URL in Telegram / LINE.

Important:
Google Sites itself cannot reliably force this preview image. The preview card will come from this hosted share page, not from the original Google Sites URL.

If a platform does not show the new image immediately:
- Telegram / Facebook / LINE may cache previews.
- Change the share URL path slightly, or use the platform's sharing debugger/cache refresh tool.
