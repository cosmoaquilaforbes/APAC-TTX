ASIA PACIFIC VISUALISER — IMAGE FOLDER
======================================

Drop image files (JPG / PNG / WEBP / GIF / SVG) into this folder,
then reference them by FILENAME ONLY when editing an event.

Example workflow
----------------
1. Save "senkaku_incident.jpg" into this folder:
     assets/images/senkaku_incident.jpg

2. Open the HTML in a browser, open the relevant event in the
   detail panel, and toggle the Live Editor.

3. In the event's Image field, type (or paste):
     senkaku_incident.jpg

   — or click the "Browse..." button and pick the file. The
   editor will prefill the filename automatically.

4. Save. The image appears in the detail panel.

Notes
-----
* Keep filenames simple: lowercase, no spaces, ASCII only.
  Good:  truk_lagoon.jpg    bad:  Truk Lagoon (final).JPG
* If an image fails to load, the editor shows an "Image not
  found" indicator — check spelling and that the file really
  is in this folder.
* Exported JSON sessions only store the filename, so the same
  scenarios can be shared with anyone who has this HTML plus
  this folder of images.
* If you need a single-file portable session (no folder), you
  can instead paste a data: URL into the Image field — the
  detail panel will render it natively.
* No internet is required. Everything resolves from files on
  disk.

Suggested subfolders
--------------------
You can organise images into subfolders and reference them with
relative paths, e.g.:
     assets/images/taiwan/strait_transit_01.jpg
In that case, put the path (minus the leading "assets/images/")
into the Image field:
     taiwan/strait_transit_01.jpg
