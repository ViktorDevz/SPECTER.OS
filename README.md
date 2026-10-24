SPECTER.OS V9.6 — DOOM repair

The previous DOOM integration mixed js-dos v7 and a remotely hosted bundle whose accessibility was uncertain. This build uses js-dos v8 with its documented bundled DOOM sample and v8 player API.

HOW TO START
1. Extract everything. Open index.html. Ideally serve the folder on localhost (python -m http.server 8000 then http://localhost:8000).
2. Type doom and Enter in the terminal. Allow up to 20 seconds for download and initialization.
3. If the remote engine/bundle fails to load, the overlay now shows an explicit fallback for choosing an authorized .jsdos game bundle from your computer.

NOTE: The remote DOOM bundle and library are third-party dependencies; working game play has not been verified in a live browser here. Public hosting requires appropriate game-content licensing. Everything else, including media, Lab, contact page, and music player, is preserved.


V9.7: Removed colored/decorative icon glyphs from dimensional controls and normalized visual accents; replaced broken overlapping central diamond with stable concentric portal and readable centered label. No changes to Doom, music, gallery or contact.


## Athena Easter Egg (v9.8)
In the terminal type `athena` (case insensitive) and press Enter. A fullscreen visual heart explosion plays. Close with button, Escape, or outside click. Reduced-motion mode disables flashes and particle animation. All previous site content is preserved.


## Athena password Easter egg
Terminal: `athena` -> enter password `1380` -> Athena heart animation. The field masks typed input; wrong password is denied. Escape cancels. Password verification is client-side JavaScript and is an Easter egg, not a secure authentication mechanism.


V10: Type `chaos mode` or `chaos` in the terminal for a controlled cinematic system-breach animation. Automatic recovery after 6.5 seconds, immediate ESC or RESTORE exit, reduced-motion support, 34 temporary fragments, no rapid flashing. The previous chaos button triggers the same effect.
