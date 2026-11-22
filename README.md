# A little something for you

Single-file surprise website. Open `index.html` in any browser (or upload it to any static host); no build step.
All 13 meme images are embedded. Fonts load from Google Fonts, with fallbacks.

Flow: surprise → food → envelopes → choose date → date question → final ticket.

Final page: "Send it on WhatsApp" draws the ticket as an image and opens the phone's share sheet,
so she can pick WhatsApp and your chat. If the share sheet isn't available (e.g. some desktops),
it saves the image and opens WhatsApp with a message, and she attaches the image.
Optional: set `WA_NUMBER` in the script (country code + digits) to pre-select your chat in that fallback.
