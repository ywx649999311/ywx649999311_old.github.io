## Built using Hugo Academic
The original repo: https://github.com/wowchemy/wowchemy-hugo-themes
The full documentation is at: https://wowchemy.com/docs/

### Basic Instructions
1. Most source markdown files are lived under `content`
2. Top bar menu and links are in `config/_default`
3. Last updated can be changed in `layouts/partials/site_footer.html`
4. CV is stored in `static/files/`
5. Icons stored in `assets`

### How to Update Publications
1. Update `static/pubs.bib` (go on ADS to generate a new one)
2. Run 
   ```bash
   academic import --overwrite --bibtex static/pubs.bib
   ```

### How to edit locally
```bash
hugo server
```
If require installation, see [here](https://wowchemy.com/docs/getting-started/install-hugo-extended/)

### How to deploy as github pages
1. Run `rm -r public/` if it exists
2. Run
   ```bash
   git add .
   git commit -m "message"
   git push
   ```
3. Run
   ```bash
   hugo
   cd public
   git add .
   git commit -m "Rebuild website"
   git push origin main
   cd ..
   ```
If above give errors, checkout this [doc](https://wowchemy.com/docs/hugo-tutorials/deployment/#github-pages) to redo the git submodule linking. 
