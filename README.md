## Built using Hugo Academic
The original repo: https://github.com/wowchemy/wowchemy-hugo-themes
The full documentation is at: https://wowchemy.com/docs/

### Basic Instructions
1. Most source markdown files are lived under `content`
2. Top bar menu and links are in `config/_default`
3. Last updated can be changed in `layouts/partials/site_footer.html`
4. CV is stored in `static/files/`
5. Vizic documentation is in `static`
6. Icons stored in `assets`

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