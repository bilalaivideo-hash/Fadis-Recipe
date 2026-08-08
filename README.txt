FADI'S RECIPE — WEBSITE PACKAGE (fadisrecipe.pk)
=================================================

WHAT'S IN THIS ZIP
-------------------
index.html      -> the full website (single file, all CSS/JS included)
images/logo.png -> your logo (already included)
images/pizza.png -> ** NOT included — see below **
robots.txt       -> tells search engines they can crawl the whole site
sitemap.xml      -> tells Google the page to index (set for fadisrecipe.pk)

IMPORTANT — ONE FILE YOU MUST ADD YOURSELF
--------------------------------------------
The hero section uses images/pizza.png (your pizza photo). I don't have
that file on my side — you added it yourself when you were testing the
site earlier. Before you upload this package:

  1. Put your pizza photo in the images/ folder
  2. Name it exactly: pizza.png
  (Recommended size: roughly 800x800px or larger, square-ish works best)

If this file is missing, everything else on the site will work fine —
only the hero image on the right side of the homepage will show as broken.

HOW TO DEPLOY TO fadisrecipe.pk
---------------------------------
1. Buy hosting (if you haven't) and point fadisrecipe.pk's nameservers /
   DNS A-record to your hosting provider's IP — your hosting company or
   registrar (e.g. PKNIC or wherever you bought fadisrecipe.pk) will give
   you these steps or do it for you.
2. Upload ALL files in this zip (index.html, robots.txt, sitemap.xml,
   and the images folder with both logo.png and pizza.png) to your
   hosting's root folder (usually called public_html or www).
3. Make sure index.html stays named exactly "index.html" — that's what
   loads automatically when someone visits fadisrecipe.pk.
4. Once live, submit https://fadisrecipe.pk/sitemap.xml in Google Search
   Console (Search Console -> Sitemaps) so Google indexes it faster.

WHAT WAS UPDATED FOR THE DOMAIN
----------------------------------
- Canonical URL set to https://fadisrecipe.pk/
- Open Graph + Twitter share tags now point to fadisrecipe.pk (so links
  shared on WhatsApp/Facebook/Instagram show your logo + title properly)
- Structured data (the FastFoodRestaurant schema Google reads) now
  includes your real domain and logo URL
- robots.txt + sitemap.xml added and pointed at fadisrecipe.pk

Nothing else was changed in this pass — design, menu, cart, and all
earlier fixes are exactly as they were.
