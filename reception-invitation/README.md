# Gowsik & Gayathri — Reception Invitation

A separate, static reception-only invitation. This project does not change your existing wedding invitation.

## Reception details

- Sunday, 13 December 2026, 7:00 PM–9:00 PM (India time).
- Sri Kamatchi Amman Thirumana Mandapam, Pollachi.
- Countdown and calendar download use the same reception time.

The time follows the printed programme. If you want a different time, update both the display in `index.html` and the countdown/calendar dates in `script.js`.

## Deploy separately on Vercel

1. Extract the ZIP. Create a **new** GitHub repository for the reception invitation, so you do not replace the existing wedding invitation.
2. Upload the contents of the extracted `reception-invitation` folder, including the `assets` folder. `index.html` should be at the repository root. If you upload the entire folder instead, set the Vercel Root Directory to `reception-invitation`.
3. Open https://vercel.com/new and import the new repository as a **new** project.
4. Set the framework preset to **Other**. No build command or output directory is needed. Deploy and share the new URL.

## WhatsApp sharing preview

The link-sharing thumbnail currently points to the same public image on the existing wedding website (`https://gowsik-gayathri-wedding.vercel.app/assets/wedding-share.jpg`). The image is also included locally in `assets/wedding-share.jpg`. To make the reception project fully independent, once you know its Vercel URL, replace the image URL in both `og:image` and `twitter:image` metadata in `index.html` with your new URL followed by `/assets/wedding-share.jpg`, then redeploy. Messaging apps may cache older link previews.

## Music and animation

The supplied Mangal Rang audio is included. The site attempts to play it automatically; browsers may require the guest to tap or click first. Guests can pause it. Verify that you have permission to share the music before publishing.

The miniature is an AI-generated illustration with simulated motion; it is not a portrait or fully articulated 3D model. Effects respect reduced-motion settings, and the illustration remains visible if WebGL is unavailable.

## Preview locally

Run `python3 -m http.server 8000` in this directory and visit `http://localhost:8000`. For the live Arena preview, the server is started on port 8001.
