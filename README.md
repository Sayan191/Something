# A little something for you

Single-file surprise website. Open `index.html` in any browser; no build step, no dependencies.
All 13 meme images are embedded in the file. Fonts load from Google Fonts (with fallbacks).

Flow: surprise → food → envelopes → choose date → date question → final ticket.

Mail-back: the final page opens the mail app to the address set in the `MAIL_TO` constant in the script.
Optional silent sending: set `FORM_ENDPOINT` and `FORM_KEY` (e.g. Web3Forms) when hosted on your own site.
