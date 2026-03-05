FAVICON ON MOBILE – YOU NEED 2 PNG FILES
========================================

Mobile (especially iOS) often does NOT show SVG favicons. To see your icon on phones:

1. favicon.png     – 32×32 px   (browser tab icon on mobile)
2. apple-touch-icon.png – 180×180 px (iOS home screen / tab icon)

How to create them from your logo (logo.svg):

• Option A – Online: Upload logo.svg to https://realfavicongenerator.net or similar, download the PNGs and save as favicon.png and apple-touch-icon.png here.

• Option B – Design tool: Open logo.svg in Figma/Illustrator/Inkscape, export at 32×32 and 180×180 as PNG. Save into this folder (images/) with the names above.

• Option C – Command line (if you have ImageMagick):
  magick convert -background none -resize 32x32 logo.svg favicon.png
  magick convert -background none -resize 180x180 logo.svg apple-touch-icon.png

Put both PNG files in this folder: E:\RMP\images\

Then the icon will show in mobile browser tabs and when users “Add to Home Screen” on iOS.
