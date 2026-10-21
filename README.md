# Terri Leigh's Cleaning Services

Website for Terri Leigh's Cleaning Services: home, building, office and oven cleaning across Hull and East Yorkshire.

It's a single static page (`index.html`) with no build step, hosted on Render as a static site. Every push to `main` goes live automatically.

Contact is by phone (07575 226399) and WhatsApp, in the Contact section of `index.html`.

## Admin: job photos

`admin.html` (linked as "Admin" in the footer) lets Terri add photos of finished jobs. They show in the "Our work" section of the homepage.

- Sign in with a GitHub fine-grained token for this repository only, with **Contents: Read and write**. The admin page explains how to make one. It's remembered on that phone.
- Uploads are shrunk to 1600px, saved in `photos/`, and listed in `photos.json`, all in one commit. Render redeploys automatically, so photos appear in about a minute.
