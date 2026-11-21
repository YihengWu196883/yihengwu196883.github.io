# Academic website for GitHub Pages

This blank template has five pages: Home, Research, Talks, Travel, and Teaching.
Open `index.html` in a browser to preview it. The site uses HTML and CSS with no
build step or third-party dependencies.

## Add your details

- Replace `Your Name` in the header and title of each HTML file.
- Fill in the biography, affiliation, email, CV, and research interests in
  `index.html`. The HTML comments show where each item goes.
- To add a portrait, put an image in `assets/` and replace the Portrait caption
  with an image such as `<img src="assets/portrait.jpg" alt="Portrait of Your Name">`.
- To link your CV, put a PDF in `assets/` and add
  `<a href="assets/cv.pdf">Download CV</a>` inside the CV entry.
- Add entries to `research.html`, `talks.html`, `travel.html`, and
  `teaching.html` as needed. Edit `assets/site.css` for shared styles.

## Publish on GitHub Pages

1. For a personal site at `https://USERNAME.github.io/`, use a repository called
   `USERNAME.github.io` and replace `USERNAME` with your GitHub username. You
   can also use an ordinary repository to host the site at
   `https://USERNAME.github.io/REPOSITORY/`.
2. Put these files at the root of the repository's `main` branch. Include
   `.nojekyll` and the `assets/` directory.
3. In the repository, open **Settings → Pages**. Choose **Deploy from a branch**,
   select **main** and **/(root)**, then save.
4. Open the live URL shown under **Settings → Pages** when deployment finishes.

See [GitHub's publishing source guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
for details.
