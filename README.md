# arunavbordoloi.github.io

Personal academic website of Arunav Bordoloi, served by GitHub Pages at https://arunavbordoloi.github.io/.

The whole site is one static page, so no build step is needed.

- `index.html`: the page. News, publications and talks are plain lists in the `<script>` block at the bottom of the file.
- `images/profile.jpg`: profile photo.
- `files/Academic_CV_Arunav_Bordoloi.pdf`: the CV linked from the page. To update it, replace this file and keep the same name, then change `CV_VERSION` in `index.html` so visitors get the new file instead of a cached copy.
- `images/share.jpg`: the image shown in link previews (LinkedIn, Slack, etc.).
- `robots.txt`, `sitemap.xml`: help search engines find the site. Update `<lastmod>` in the sitemap after big changes.
- `404.html`: sends visitors who follow links to the old site's pages to the matching section here.
- `favicon.*`, `apple-touch-icon.png`: browser tab and home-screen icons.

To update the site, edit these files and push to `master`. GitHub Pages republishes within a minute or two.
