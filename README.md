# Diff Desk — Day 09

Compare two versions of text and review added, removed, and unchanged lines. Diff Desk works with drafts, configuration, code snippets, and other plain text without sending the contents to a server.

## Use it

Open `index.html` or visit the live demo. Paste or open a local text file in each panel, choose optional matching rules, then select **Compare text**. Copy the result or download it as a `.diff` text file.

## Features

- Side-by-side original and updated text editors.
- Line-based added, removed, and unchanged highlighting with line numbers.
- Optional ignore-whitespace, ignore-case, and ignore-blank-line matching.
- Open common plain-text files from your device.
- Added, removed, unchanged, and similarity summary.
- Copy the diff or save it locally as a `.diff` file.
- Runs in the browser with no account, upload, analytics, or external libraries.

## Privacy and limits

Text is processed in the current browser tab and is not uploaded or stored by the app. Matching is line-based, so it does not highlight edits within a single line character by character. To keep the browser responsive, the comparison is capped at about 1.2 million line-pair comparisons; compare smaller sections for larger files. The whitespace option ignores all whitespace when matching, while the display preserves each original line.

## GitHub Pages

This is a static single-file app. GitHub Pages can serve it from the repository's `main` branch and root folder.

## Built with

HTML, CSS, and browser JavaScript. MIT License.
