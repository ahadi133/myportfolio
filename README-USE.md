# Using this portfolio

Open this folder in VS Code and click **Go Live**. The portfolio opens at `index.html`.

To edit it, manually open `admin.html` in the same Live Server site. It is deliberately
not linked from the public navigation. Sign in with the ROBIN account, make your edits,
then click **Download updated data.js**. Replace the existing `data.js` in this folder
with the downloaded file and refresh the portfolio.

This is intentionally a simple static-site editor: it needs no npm, database, cloud
account, or deployment setup. It is private on your own computer, but it is **not** a
secure web backend and should never be published as a real protected admin system.

For GitHub Pages, upload the whole folder but remove `admin.html` first.
