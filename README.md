# manavijadhav — website

Plain HTML/CSS site with no build step. Six pages: index, research, space-health, expeditions, outreach, about.

## Put it on GitHub Pages
1. Create a new repository on GitHub and upload everything in this folder (keep the `css`, `js` and `images` folders).
2. Go to Settings > Pages, set Source to "Deploy from a branch", pick `main` and `/ (root)`, and save.
3. The site appears at `https://<your-username>.github.io/<repo-name>/` after a minute or two.

## Filling in the gaps
Missing information is shown as yellow dashed boxes that start with "To add:".
Search the HTML files for `To add` to find every one, replace the text, and delete the surrounding `<span class="todo">` or `<div class="photo-todo">`.

To add a photo where a yellow box is, replace the box with:
`<img src="images/your-photo.jpg" alt="Short description of the photo">`

## Moving to Wix or WordPress later
Each page's text sits between `<main>` and `</main>`, so it can be copied section by section.
The colours and fonts are at the top of `css/style.css`.
