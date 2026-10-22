# Review comments

Collect pinned comments on any HTML file in this repo. Comments save to a shared Google Sheet.

## Sharing a file for review

1. Upload the HTML file to this repo (same folder as `review.html`, or a subfolder).
2. Share this link, with your file name at the end:

   `https://<your-username>.github.io/<repo-name>/review.html?page=<file-name>.html`

   For a file in a subfolder: `?page=emails/state_alert.html`

Optional: add `&width=desktop` or `&width=phone` to open at that width. The default is email width (680 px).

`review.html` on its own (no `?page=`) lists every page that has comments.

## Where comments go

The **Comments** tab in the Google Sheet: one row per comment with page URL, section, comment, name, status and a review link that opens straight to that comment's pin.

## Good to know

- Files must be on the same GitHub Pages site as `review.html`.
- New comments from other people show up within 30 seconds, or on reload.
- If you replace a file with a new version under the same name, existing comments stay with it. Comments on parts that were removed show as "Not pinned" in the sidebar.
- Changing `Code.gs` later? In Apps Script, go to **Deploy → Manage deployments → Edit → Version: New version → Deploy**. The web app URL stays the same.
