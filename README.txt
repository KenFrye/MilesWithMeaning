Miles With Meaning v2.1 — GitHub-ready production build

This is based on the approved Miles With Meaning Version 2 design. It is an enhancement, not a redesign.

Changes in v2.1:
- Navigation: Home, Current Campaigns, Highlights, Partners, About, Donate
- Current Campaign renamed to Current Campaigns
- "Coming Up" section for the next campaign
- New Highlights preview on the homepage
- New highlights.html page for photos, videos, runs, rides, fundraisers, volunteering, and community stories
- Partners & Causes section added
- Existing hero, colors, typography, donation flow, impact section, and overall design preserved

EASY UPDATES
Most frequently changed content is in site-config.js:
- fundraising totals
- campaign name/date
- upcoming campaign
- social links
- donation links
- Highlights

TO ADD A HIGHLIGHT
1. Put a photo or video in /assets (optional).
2. Open site-config.js.
3. Copy one object inside the highlights array.
4. Change title, date, category, summary, mediaType, media, and icon.
5. Commit and push to GitHub.

mediaType can be:
- "image" with media: "assets/your-photo.jpg"
- "video" with media: "assets/your-video.mp4"
- "icon" with media: "" and an emoji in icon

DEPLOYMENT
Upload these files to the root of the MilesWithMeaning GitHub repository. Netlify can then be connected to the repository for automatic deployment from the main branch.
