# Detention Intelligence Management System (prototype)

A working prototype of a jail intelligence tool for the Bexar County Sheriff's Office Adult Detention Center: intel reports, contraband finds, subjects and dossiers, link analysis, a facility risk map, collection planning, and a Jail Blotter module that reads the daily Word blotters and monthly Excel workbooks. It includes trend analysis and custom pattern rules.

**This is a prototype for testing, not a production system.**

## Try it

- **Online:** once GitHub Pages is on (below), the app is at `https://<your-account>.github.io/<repository-name>/`.
- **On your own computer:** download `index.html` and double-click it. It opens in your browser and works without internet; everything it needs is inside the one file.

## Where data is kept

- Everything you enter or import is stored **only in the browser you're using, on that computer**. Nothing is uploaded, and nothing is shared with anyone else who opens the same page.
- The intel reports, subjects, sources and contraband finds that come with the app are **fictional sample records**. The Jail Blotter starts empty.
- **Before importing real blotters or entering real information into a copy hosted on GitHub Pages**, check with your agency. The data still stays in your browser, but the page itself is on a public service. For real data, open the downloaded file locally, or use the SharePoint build described in the build guide.

## Publish it with GitHub Pages

1. Create a repository and upload `index.html`, `README.md`, `THIRD_PARTY_NOTICES.md` and `.nojekyll`.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/ (root)**, then **Save**.
4. After a minute or two the address appears at the top of the Pages settings.

A Pages site is visible to anyone who has its address. Publishing Pages from a **private** repository needs a paid GitHub plan (Pro, Team or Enterprise).

## Browsers

Current Chrome, Edge, Firefox and Safari. On a phone or tablet, open the file in the browser (**Share → Open in**), not in the file preview, which doesn't run the app. If the app can't start, the page says why instead of staying blank.

## Updating

The app is a single file. To update, replace `index.html` with the new version and commit; Pages republishes automatically.

## Built-in components

The app embeds SheetJS, mammoth.js, jsPDF and the Barlow fonts so it works offline. See `THIRD_PARTY_NOTICES.md` for their licences.
