# Roland Earl & Ana Marie — Wedding Invitation

An e-wedding invitation web page.

**Date:** 12 December 2026, 3:30 PM
**Venue:** Le Jardin De Teodoro at San Rafael River Adventure, San Rafael, Bulacan
**Theme:** Spring / Sunflower · "Honey Silk" palette

## View it

Open `index.html` in any web browser.

## Publish it free with GitHub Pages

1. Create a new GitHub repository and upload **all** the files in this folder (keep them together).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/ (root)**, then **Save**.
5. Wait ~1 minute. Your invitation will be live at:
   `https://<your-username>.github.io/<repo-name>/`

Share that link with your guests.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The invitation page (all layout, styling, and scripts) |
| `wedding.ics` | Calendar event file the "Add to Calendar" button links to |
| `hero.jpg` | Hero banner photo |
| `together-bikes.jpg` | "Together, at last" photo (the couple with their bikes) |
| `g001.jpg` – `g169.jpg` | Photos in the "The Couple" scrolling carousel |
| `seal.png` | Wax seal on the opening envelope |
| `rings.png` | Wedding rings between the couple's names in the hero |
| `sunflower-corner.jpg` | Watercolor corners (hero + footer) |
| `carousel-border-top.png` / `carousel-border-bottom.png` | Sunflower borders framing the carousel |
| `sunflower-basket.png` | Accent above the countdown |
| `sunflower-frame.webp` | Frame around the wedding date |
| `tl-sunflower.png` | Sunflower bullet markers on the timeline |
| `venue-map.png` | Resort map on the front of the Venue Guide flip card |
| `entourage.jpg` | The Entourage design (Primary/Secondary Sponsors, Officiating Minister) |
| `dress-code3.jpg` | Dress code guide (attire section) |
| `bg-rsvp.jpg` | Sunflower pattern filling the RSVP section background |
| `sunflower-reminder.png` | Unplugged-ceremony reminder graphic |

## Sections

Envelope intro (tap to open) · Hero · The Couple (photo carousel) · Countdown ·
Together, at last (portrait) · The Celebration (date & venue) · Venue Guide (tap-to-flip map/guide card) ·
Wedding Day Timeline · Entourage (sunflower-framed sponsor list) · The Palette · Dress Code · Unplugged-ceremony note · RSVP · Footer

## RSVP

The RSVP is an **embedded Google Form**. Responses are collected automatically
in the linked Google Sheet on the form owner's Google account. To change the
form, edit it in Google Forms — updates appear on the page automatically.
The form is embedded via the `<iframe>` in the RSVP section of `index.html`.

## Features

- Floating quick-nav menu (hamburger, top-left) to jump to any section
- Envelope opening animation on load
- Tap-to-flip Venue Guide card (resort map flips over to reveal the arrival guide)
- Auto-scrolling photo carousel of the couple
- Live countdown to the wedding day
- "Add to Calendar" button (downloads a calendar event)
- "View Map" link to the venue
- Embedded Google Form RSVP
- Responsive — works on phones and desktops

## Notes

- External dependencies loaded from the internet: Google Fonts and the Google
  Form. An internet connection is needed for those to display.
- All images have been optimized for fast loading (the full page, including the
  169-photo carousel, is roughly 5.5 MB and the photos are lazy-loaded).
