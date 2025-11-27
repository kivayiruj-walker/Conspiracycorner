# Conspiracy Corner

This branch (improve-navigation) contains accessibility, navigation, and styling improvements and three sample article pages. It also includes a placeholder area for Google AdSense. Review the changes in the branch and open a pull request to merge into main when ready.

How to preview locally

1. Clone the repo and switch to the branch:

   git clone https://github.com/kivayiruj-walker/Conspiracycorner.git
   cd Conspiracycorner
   git checkout improve-navigation

2. Open index.html in your browser or serve with a simple static server (recommended):

   python -m http.server 8000
   # then visit http://localhost:8000

Google AdSense placeholder

A placeholder comment has been added to the ads section in index.html. When you're ready, replace the placeholder with your AdSense snippet. Example:

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXX" crossorigin="anonymous"></script>

Then add an ad block with your client and ad-slot IDs.

Publishing with GitHub Pages

1. On GitHub, go to Settings → Pages and choose the branch `main` (or `improve-navigation` to preview) and the root folder.
2. Save and wait a few minutes for the site to publish.

Notes

- I have not added a real AdSense ID. Update the placeholder before enabling ads.
- Review content for accuracy and compliance with ad policies before monetizing.
