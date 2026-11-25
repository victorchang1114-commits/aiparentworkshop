# Parent AI Learning Kit / 親子 AI 練習室

A bilingual parent handout with prompt examples, a local prompt builder, print support and a PDF download. Plain HTML, CSS and JavaScript; no installation, build process or API key required.

## Publish on GitHub Pages

1. Create a public GitHub repository, for example `parent-ai-handout`.
2. Upload the **contents** of this folder (not the ZIP) to the repository root. `index.html` and `handout.pdf` must be beside each other.
3. Commit the files to `main`.
4. Open **Settings > Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select **main** and **/(root)**, then **Save**.
7. Once deployment completes, open the address shown in Pages settings, normally `https://YOUR-USERNAME.github.io/parent-ai-handout/`.

Official guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Files

- `index.html`: complete website, styles, interaction logic and bilingual prompt content.
- `handout.pdf`: printable bilingual companion; keep this filename or update its link in the HTML.
- `.nojekyll`: tells GitHub Pages to serve the static files directly.

## Editing

Open `index.html` in a text editor. Styles are in `<style>`, content and logic in `<script>`. The `data` array contains the nine bilingual examples. Editing the website does not automatically update the PDF; replace that separately when necessary.

The site uses relative PDF links and works under a GitHub project subdirectory. The prompt builder formats text locally; it does not call an AI service. Form entries are not saved and clear on reload. Copy buttons work best on the published HTTPS site; manual copying remains available if the browser blocks clipboard access.

## 中文發布步驟

解壓縮後，把資料夾內的檔案上載到 GitHub repository 最外層，並提交到 main。到 Settings > Pages，選 Deploy from a branch，再選 main 和 /(root)，按 Save。完成部署後即可把 Pages 網址分享給家長。請勿只上載 ZIP，或把 index.html 放到額外子資料夾。
