GALACTIC GLIMPSEZ - one-file website
====================================
This folder has only:
  index.html  = the whole site (design, code, text, logo, events, page navigation)
  8 photos    = Andromeda_final.jpg, M_31.jpg, M_45.jpg, IMG_3246.jpg, Himalayan_star_trails.jpg,
                IMG_0568.jpg, IMG_3430.jpg, Geminids_meteorshower.jpg
Keep the photos in the SAME folder as index.html. Do not rename them.
Photos are separate files on purpose: putting them inside index.html would make the page about 8 MB and slow to open.

TEST: double-click index.html.

PUT IT LIVE ON RENDER (free)
 1. Upload index.html and the 8 photos to a GitHub repository, all at the top level (no folders).
 2. render.com > New > Static Site > pick the repository.
 3. Build Command: leave empty (or  echo ok ).   Publish Directory:  .   (one dot)
 4. Create. Later changes: upload the changed file to GitHub; Render redeploys automatically.
 If only a blank page shows, the photos or index.html are not at the top level of the repository.

OTHER FREE HOSTS: Cloudflare Pages (Upload assets), Netlify Drop (drag the folder), GitHub Pages. All work the same way.

HOW ADNAN CHANGES THINGS
 Open index.html in Notepad/VS Code. At the top of the <script> is the block "CONTENT: EDIT THIS BLOCK ONLY":
  - about, gear, email, social links, tagline, background photo
  - photos [ ... ]  : one line per photo
  - events [ ... ]  : one line per event (an example is in the comment)
 To get ready-made lines, open the live site address followed by  /#/admin  (for example yoursite.onrender.com/#/admin),
 fill the form and paste the copied line into photos or events. Then upload index.html (and any new photo) again.
 New photo: resize to about 2500 px on the long edge, save as .jpg, copy next to index.html, add its line.

LATER: CONNECTING galacticglimpsez.in
 Buy the domain at any registrar that sells .in. In Render open the site > Settings > Custom Domains, add
 galacticglimpsez.in and www.galacticglimpsez.in, and set the DNS records Render shows at your registrar.
 HTTPS is added automatically. Then set email and social links in the CONTENT block.
