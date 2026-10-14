# Toosi Tailor — Progress

**Status:** Website complete. Hosted via GitHub → Vercel (no StackBlitz, no editor needed).

## Done
- Full React (Vite) portfolio, blue + gold theme, scroll animations
- Mobile responsive (viewport tag now lives in `index.html`)
- Dark / Light mode button and English / Urdu (RTL) button
- Your photo (About) and your father's photo (top of Home), both real images
- Gallery uses your 4 banner images; tap an image to view it full size
- Sherwani and Wedding Packages removed (English + Urdu); Waistcoats and Trousers added
- Fixed shop GPS 30.227312, 71.472216 with "Get Directions" route button
- WhatsApp button and the contact form open WhatsApp with the customer's message
- "About Programmer" card in the footer (English + Urdu), email 555hasnainkhan@gmail.com

## Where things are
| What | File |
|---|---|
| Your photo | `public/images/profile.jpg` |
| Father's photo | `public/images/dad.jpg` |
| Gallery | `public/images/gallery-1..4.jpg` |
| All text (English + Urdu) | `src/App.jsx` (top, object `T`) |
| Share preview image | `public/share-banner.jpg` |

To change a photo: on GitHub open the file → **Delete**, then upload a new one with the **same name**. Vercel redeploys by itself.

## Open items
- [ ] Location text says "Multan" but your banner says "Dunyapur, Distt. Lodhran" — confirm which is right (`locV` in `src/App.jsx`)
- [ ] After deploy, put your real link in `index.html` → `og:image` so WhatsApp previews show the banner
- [ ] Replace the 3 sample customer reviews with real ones
- [ ] Father's name is not written anywhere; add it next to the founder photo if you want
