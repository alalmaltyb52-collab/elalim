# Elalim Mohamed — V3 CMS Website

This version adds a private Admin Dashboard using Decap CMS. Content is stored in `content/site.json`; publishing from `/admin/` commits the updated content to GitHub, and Netlify rebuilds the public website automatically.

## One-time setup
1. Create a GitHub repository and upload this project.
2. Import the repository into Netlify. Build command: `npm run build`; publish directory: `dist`.
3. Enable Netlify Identity and set Registration to **Invite only**.
4. Enable Git Gateway.
5. Invite your own email address as the only CMS user.
6. Connect `elalimmohamed.com` to the Netlify site and enable HTTPS.

## Daily use
Open `https://elalimmohamed.com/admin/`, sign in, edit Website Content, then Publish. You can add publications, posts/updates, research areas, experience, projects, achievements, social links and other content without editing code.

## Important
Review the publication list and profile wording before the public launch. Keep the CMS registration invite-only so only you can edit the site.
