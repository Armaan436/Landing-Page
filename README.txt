teenage engineering — Bootstrap version
========================================

This is the site rebuilt on the Bootstrap 5 framework, structured for
editing in Adobe Dreamweaver.

Pages
-----
- index.html      home (navbar, hero, bestsellers, sample form)
- about.html      about us
- products.html   product catalogue (6 items)
- sample.html     free sample kit form
- css/style.css   custom TE theme (loads AFTER Bootstrap)
- assets/         your images

How it's built
--------------
- Bootstrap 5.3.3 is loaded from a CDN in each page's <head> (CSS) and
  before </body> (JS bundle for the mobile navbar toggle).
- Layout uses Bootstrap's grid (container/row/col), navbar, card, and
  form-control / form-select components.
- css/style.css holds the teenage-engineering look (orange accent,
  lowercase type, Space Mono labels). It is linked AFTER Bootstrap so
  its rules override the defaults.

Opening in Dreamweaver
----------------------
1. File > Open, or set up a Site pointing at this folder.
2. Edit pages in Code or Split view. Live view needs an internet
   connection so the Bootstrap CDN and Google Fonts load.
3. To work fully offline, download bootstrap.min.css and
   bootstrap.bundle.min.js into a /vendor folder and change the CDN
   links to local paths.

Note on images
--------------
The product photos in /assets were supplied in the uploaded project.
Make sure you have the rights to use them before publishing the site.
