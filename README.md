# Shailesh PDF Super Editor

A free, open PDF annotation app that runs entirely in your browser. Nothing is uploaded: your PDF stays on your device.

**Open the app:** https://astroidturtle.github.io/shailesh-pdf-super-editor/  
**Product page:** https://astroidturtle.github.io/shailesh-pdf-super-editor/product/

## What it does

- **Mark up PDFs:** highlight, underline, strikeout, text boxes, callouts, pop-up notes, stamps, rectangles, ellipses, clouds, lines, arrows, polylines, pictures and file attachments.
- **Pen tablets:** pressure-sensitive ink, palm rejection ("Pen only"), pen eraser tip and barrel-button lasso, hold-to-straighten, brush preview, and a floating pen dock with big buttons.
- **Saves real PDF annotations** that open in Acrobat, Preview, Edge and other readers.
- **Search, grid, night page, export notes to Markdown.**

## AI review (bring your own key)

Open **AI & Friends → AI connections** and paste an Anthropic and/or OpenAI API key. Then:

- **Summarize this PDF:** a synopsis with page references.
- **Ask Claude:** questions answered from the PDF's text.
- **Claude / ChatGPT reviews the PDF:** comments pinned onto the exact lines.
- **Digest:** where reviewers agree, disagree, and what to do next.

Keys are stored only in your browser and sent only to Anthropic or OpenAI. No key? Use **Copy prompt for ChatGPT** and **Import ChatGPT reply** instead.

## Reviewing with friends

1. Each person opens the same PDF in the app.
2. **Library → Export review file** saves your marks and suggestions as a small `.json` file.
3. Send it to a friend; they choose **Import review files**. Files merge, so everyone ends up with everyone's comments.

## Keyboard shortcuts

`V` select · `P` pen · `1 2 3` red/green/blue pen · `4` highlighter pen · `H` highlight · `E` eraser · `T` text box · `S` stamp · `[ ]` size · `Ctrl+F` search · `Ctrl+Z / Y` undo/redo · `?` all shortcuts

## Hosting

This is a single static file (`index.html`). GitHub Pages serves it from the repository root (Settings → Pages → Deploy from branch → `main` / root).

## Edit, test and repost (for friends)

1. **Test:** open the app link at the top of this page. Product page: `/product/`.
2. **Edit in your browser, no install:** on this repo page press the `.` key (or open https://github.dev/astroidturtle/shailesh-pdf-super-editor). The app is `index.html`; the product page is `product/index.html`.
3. **Save your changes:** in the editor's Source Control panel, commit.
   - If you were added as a collaborator, it goes straight onto the live site within about a minute.
   - If not, GitHub offers to **fork** the repo. Commit to your fork, then click **Contribute → Open pull request** to send the change back.
4. **Host your own copy (optional):** in your fork, go to Settings → Pages, choose Deploy from a branch → `main` / root. It appears at `https://<your-username>.github.io/shailesh-pdf-super-editor/`.

Found a bug or have an idea? Open an issue: https://github.com/astroidturtle/shailesh-pdf-super-editor/issues
