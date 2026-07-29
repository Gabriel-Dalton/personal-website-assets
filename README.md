# personal-website-assets

The asset host for gabrieldalton.com, published by GitHub Pages at https://assets.gabrieldalton.com. Every file in here is already a live URL that something else links to.

## Do not restructure this repo

Paths are the contract. Renaming a file, moving one into a folder, changing a folder name or deleting anything breaks the links that point at it from the main site and from documents already sent out. Those links live outside this repo, so nothing here will warn you before they break.

Adding a new file is safe. Touching a path that already exists is not.

`.nojekyll` stops GitHub Pages from running Jekyll over the tree, which would otherwise drop directories it treats as special. `CNAME` binds the custom domain. Leave both in place.

## What is here

- `assets/` styles, scripts, images, logos, icons, favicons and project screenshots used by the site
- `References/` recommendation and recognition letters as PDFs
- `TKS/` project decks
- `other/` certificates
- `index.html` the page served at the domain root

Fixing something means uploading a corrected file under a new name and repointing whatever links to it, not editing paths in place.
