# Imprint

Imprint is an Android app that puts your watermark on photos, PDFs and videos. Make a mark once, from
words, a logo, shapes, a signature or a QR code, and use it again and again. It has no adverts, no accounts
and no paid version, and your photos never leave your phone.

- Website: https://customgpter.github.io/imprint/
- Latest app file: https://github.com/CustomGPTer/imprint/releases/latest
- Privacy: https://customgpter.github.io/imprint/privacy.html

## Good to know before you start

- **Removing Imprint deletes your library.** Watermarks, presets, brand kits and added fonts live inside
  the app. Save a backup file from Settings before you uninstall it or change phone. Photos, PDFs and
  videos you have already saved are not affected.
- **Your originals are never changed.** Copies go to Pictures, Documents and Movies, each in a folder
  called Imprint.
- **The extras are switched off to begin with.** Live stamps, location, brand kits, signature and QR code,
  PDF page numbers and moving video marks are switches under Settings, More tools.
- **Location needs a switch.** Android's photo picker removes the place a photo was taken. Switch on
  Location and Imprint asks to see your photos and uses its own photo list instead.
- **Keep Imprint open while a batch or a video saves.** Android may stop it if the app is swiped away.
- **A watermark deters copying; it cannot prevent it.** A tiled mark is much harder to remove than one in
  a corner.

## What it does

- Watermarks on photos (JPG, PNG or WebP), PDFs and videos (MP4, with the sound kept)
- An editor with words, logos and 14 shapes, outline, shadow, glow, bent text, undo and redo
- 120 starter designs in eight groups
- 1,824 typefaces: 204 built in, the rest fetched from Google Fonts on first use, plus your own font files
- Single, tiled and cross placements, with size, strength, a colour filter and automatic light or dark
- Batches of photos with a review strip
- Last used, favourites, presets and brand kits
- Live stamps: date, time, year, file name, running number, project, coordinates and address
- Signature drawn with a finger, and QR codes
- PDFs keep their real, searchable text; page ranges, behind or over the page, headers and page numbers
- Video marks that appear, leave, fade, bounce around or drift across the frame
- Quality, resizing, file names from a pattern, photo details kept or left out, your name written in
- A backup file for everything you have made

## What it cannot do

A visible watermark can be cropped off or edited out by someone determined. Password-locked PDFs are
refused. On a PDF the watermark itself is a picture, though the page's own text is untouched. PDFs and
videos are done one at a time. SVG logos are not accepted. Imprint is new, and this first version was
checked with automated tests on a computer and has not yet been tried across a range of phones; saving a
video depends on each phone's own encoder. If something does not work on yours, please open an issue.

## Typefaces

Every typeface comes from Google Fonts under an open licence. The list, with each family's licence and
copyright notice, is in `android/app/src/main/assets/licences`, and on the
[licences page](https://customgpter.github.io/imprint/licences.html).

## Licence

© 2026 Jonathan Jackson. All rights reserved. The app's source code is not published; this repository holds the website and the app releases.
