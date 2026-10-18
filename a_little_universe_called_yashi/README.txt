A LITTLE UNIVERSE CALLED YASHI
===============================

FILES
- index.html: the complete website (HTML, CSS, and JavaScript in one file)
- photos/: put copies of your photos here if you want to include them permanently in the published site

PREVIEW ON YOUR MAC
1. Download and unzip the folder.
2. Open the folder in Finder.
3. Double-click index.html. It should open in your browser.
4. Try the note cards, stars, and photo picker.

IMPORTANT ABOUT PHOTOS
The photo picker on the website creates local previews only. Those previews disappear when the page is reloaded.
To publish photos permanently:
1. Copy up to six image files into the photos folder, named photo1.jpg, photo2.jpg, ... photo6.jpg.
2. In index.html, find the line `for(let i=1;i<=6;i++){`.
3. This template's photo slots are upload previews. For permanent published photos, the simplest approach is to replace each photo slot with an image element, for example:
   <div class="photo"><img src="photos/photo1.jpg" alt="A favourite memory"></div>
   Repeat for the photos you want, changing photo1.jpg to photo2.jpg, etc.
4. Save index.html and refresh the browser.

CUSTOMISE THE WORDS
Open index.html in a plain-text/code editor. Search for:
- `const notes = [` to edit the hidden notes.
- `const starWishes = [` to edit wishes behind the stars.
- The section with `id="poem"` to change the poem.
- The section with `id="letterContent"` to change the birthday letter.
Don't put private information such as addresses, phone numbers, passwords, or sensitive details on a public website.

PUBLISH FOR FREE WITH GITHUB PAGES
1. Create or sign in to a GitHub account at https://github.com/
2. Create a new repository. A name such as `yashi-birthday` is fine.
3. If offered a visibility choice, choose Public (GitHub Pages on the free plan generally needs a public repository).
4. Upload index.html and any permanent photo files/folders. Keep index.html at the repository root, not inside another folder.
5. Open the repository's Settings.
6. In the left sidebar, select Pages.
7. Under Build and deployment, select “Deploy from a branch”.
8. Choose branch `main` and folder `/(root)`, then Save.
9. Wait a few minutes. The Pages screen should show the published URL, usually:
   https://YOUR-USERNAME.github.io/yashi-birthday/
10. Open that URL on your phone to test it, then send the link to Yashi.

SAFETY / PRIVACY
GitHub Pages sites are public. Anyone with the URL may be able to visit, and public repositories expose the source code too. Only upload photos and writing you are comfortable sharing publicly. If you prefer to keep the site private, keep it as a local file instead of publishing it.
