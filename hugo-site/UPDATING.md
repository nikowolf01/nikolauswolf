# Updating Nikolaus Wolf's website

Most content lives in `content/`. Each publication has its own folder under `content/publication/` with an `index.md` file.

## Add a publication

1. Copy an existing publication folder and rename it with a short permanent slug.
2. Edit its `index.md`: title, date, authors, venue, type, tab, and tags.
3. Add any downloadable paper to `static/files/` and link to it without a leading slash.

## Update the biography or contact details

Edit `content/bio/_index.md` or `content/contact/_index.md`. Replace the downloadable C.V. at `static/files/nikolaus-wolf-cv.pdf` while keeping that filename.

## Update the portrait

Replace `static/images/nikolaus-wolf.jpg` with a square image using the same filename.

## People page review

The People page was populated from co-authors named in the C.V. External links were deliberately left blank rather than guessed. Review every person before adding links to `data/coauthors.json`.

## Preview

From `hugo-site/`, run `hugo server` and open the local address Hugo prints.

