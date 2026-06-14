# Claude Code Export Viewer

A tiny, single-file web tool that turns a raw Claude Code conversation export into a clean, readable HTML log — right in your browser.

**Live app:** https://paulmvpbuild.github.io/claude-code-export-viewer/

## What it does

1. Run `/export` in Claude Code to export a useful conversation. This gives you a `.txt` file.
2. Open the [live app](https://paulmvpbuild.github.io/claude-code-export-viewer/).
3. Drag and drop the `.txt` export onto the page (or click to browse).
4. The tool converts it into a clean, readable HTML log that you can open and share.

Everything runs **locally in your browser**. Nothing is uploaded — the file never leaves your machine.

## Why

Claude Code exports are plain text and not especially pleasant to read or share. This viewer reformats them into a styled, scannable conversation log with no install, no account, and no server.

## Running it locally

It's a single static HTML file — no build step, no dependencies. Just open `index.html` in any modern browser:

```bash
open index.html        # macOS
# or simply double-click the file
```

`index.html` and `ClaudeCodeExportViewer.html` are the same file; `index.html` is the copy served by GitHub Pages.

## License

Free to use. Provided as-is, as a small gift to the community.
