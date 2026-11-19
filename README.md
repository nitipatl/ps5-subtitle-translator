# แปลซับ PS5 (ps5-subtitle-translator)

Single-page HTML5 app: iPhone rear camera → crop TV subtitle strip → Gemini `generateContent` → large Thai subtitles.
No build step, no backend. The Gemini API key is stored only in the browser's localStorage and is sent only to
`generativelanguage.googleapis.com` (enforced by the page's CSP `connect-src`).

Open `index.html` over HTTPS (camera needs a secure context). Live: https://nitipatl.github.io/ps5-subtitle-translator/
