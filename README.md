# Hampton University Technology & AI Center — Marketing Site Starter

Clean React/Vite starter for the HTAIC fundraising and marketing experience.

## Locked visual/content rules
- The supplied Hampton University logos are included in `public/images/` and should be used as the brand source assets.
- The Design Vision statement in `src/main.jsx` is the supplied project statement.
- `18–68` is Hampton student/alumni tradition referencing the 1868 founding year only. Do not use it as a metric, count, technology claim, fundraising statistic, or project KPI.
- The Hampton Student Center image is the only project-building exterior. Do not substitute or generate a different exterior. Alternate treatments may only stylize that same building as a hologram/blueprint/sketch.
- `hampton-campus-waterfront.png` is the exact supplied campus scenery used for the animated “coming to campus” portal transition. Keep the scenery photograph itself unchanged.

## Navigation
Home, Vision, Spaces, Technology, Impact, Videos, News, Contact, and Invest are wired as clickable views. The portal transition animates a boat traveling across the Hampton waterfront before the next screen loads.

## Video hosting
The Videos screen is Cloudinary-ready. In `src/main.jsx`, replace `YOUR_CLOUD_NAME` and each sample `video-N.mp4` source with the Cloudinary delivery URL for the final Hampton videos. Do not commit large production video files to GitHub.

## Donation
The Invest button opens the starter Invest view. Replace the `MAKE A GIFT` placeholder `href="#"` with Hampton University's approved donation URL before publishing.

## Run locally
```bash
npm install
npm run dev
```

## Deploy
Push the folder to GitHub and import the repository into Vercel. Vite's production build command is `npm run build`; output directory is `dist`.
