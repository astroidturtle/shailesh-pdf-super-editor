# Shailesh PDF Super Editor

A free, open PDF annotation app that runs entirely in your browser. Nothing is uploaded: your PDF stays on your device.

**Open the app:** `https://<your-github-username>.github.io/shailesh-pdf-super-editor/`

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
