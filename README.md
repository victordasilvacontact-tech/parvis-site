# parvis-site

Static landing page of Parvis (English `index.html`, French `fr.html`, `legal.html`). No build step, no cookies, no third-party script or font.

Preview: `python3 -m http.server 8765`, then open http://localhost:8765/.

Before publishing, replace `CONTACT_EMAIL`, settle every `[TO DECIDE]` in `legal.html`, and restore the buy button (`CHECKOUT_URL`, see the `TODO` comment in both pages).

Source of truth: `docs/superpowers/sales/site/` in the private product repository; copy the files here after a change.
