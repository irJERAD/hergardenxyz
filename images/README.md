# Photo file names

Drop a file with one of these names into this folder and it replaces the placeholder.
`.jpg` is expected. If you use `.webp` or `.png`, change the extension in the matching `src="images/..."` in the HTML.

## Home page (index.html)
- hero.jpg: large arch photo at the top
- hero-small.jpg: small round photo
- garden-01.jpg to garden-07.jpg: garden mosaic (01 is tall)
- family-01.jpg, home-01.jpg: the "Us" pair
- tahiti-01.jpg to tahiti-03.jpg: Tahiti section
- portrait.jpg: the About photo (square works best)

## Garden page (garden.html)
- season-01.jpg to season-08.jpg. Each tile's season is set by `data-season` in the HTML.

## Collages (index.html and collages.html)
- collage-01.jpg to collage-03.jpg: the three on the home page (the same files are the first three on the collages page)
- collage-04.jpg to collage-09.jpg, collage-studio.jpg: the rest of the collages page
- Tiles keep their shape class (`r34`, `r43`, `r11`, `r45`) in `collages.html`; change it to match each piece.

## Family page (us.html)
- family-featured.jpg, home-02.jpg to home-04.jpg

## Tahiti page (tahiti.html)
- tahiti-hero.jpg, tahiti-story-01.jpg to tahiti-story-03.jpg, tahiti-wall-01.jpg to tahiti-wall-04.jpg

## Blog post (post.html)
- post-lead.jpg, post-02.jpg, post-03.jpg

Tip: add a short description to each photo's `alt="..."` so the site works for screen readers.
