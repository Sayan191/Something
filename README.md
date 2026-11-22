# A little something for you

Single-file surprise website. Open `index.html` in any browser (or upload it to any static host); no build step.
All 13 meme images are embedded. Fonts load from Google Fonts, with fallbacks.

Flow: surprise → food → envelopes → choose date → date question → final ticket.

Final page: "Send it on WhatsApp" draws the ticket as an image, uploads it to Google Drive through an
Apps Script web app (`DRIVE_URL` in the script), then opens a WhatsApp chat with `WA_NUMBER` with the message
and the image link already typed. The script must return the file link (see the Apps Script code given in chat)
and the page must be hosted on a normal web address.
If the upload fails, WhatsApp still opens with the text only.
