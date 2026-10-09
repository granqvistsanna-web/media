# media

Public hand-off for files placed on public Framer sites: video loops, PDFs, audio.

Framer's `uploadFile` only fetches from an http(s) URL. A file pushed here is served at a
commit-pinned jsDelivr URL, Framer copies it into its own CDN (`framerusercontent.com`), and the
live site never loads from this repo.

```
<project>/<YYYY-MM-DD>-<name>
https://cdn.jsdelivr.net/gh/granqvistsanna-web/media@<commit>/<project>/<YYYY-MM-DD>-<name>
```

- Only files that are published on a public site anyway. Nothing private.
- A new version is a new file; nothing is overwritten.
- Max 20 MB per file (jsDelivr limit).
