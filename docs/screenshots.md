# Screenshot notes

The user supplied these unedited Windows Tine screenshots after installing the 0.2.0 dual-mode package:

| File | What it shows |
| --- | --- |
| nord-dark.png | Nord · Prism dark palette on the public Welcome to Tine page |
| nord-light.png | Nord · Prism light palette on the same page; a real palette, not host fallback |

The captures show public sample content in a graph named Theme, without visible personal notes or account details. Both have the same image dimensions and page position, with no text selection or active block editor. The exact Tine build is not visible, so no screenshot-specific build number is asserted. The manifest pins both image URLs to the immutable screenshot commit.

Visible coverage: headings, body text, emphasis, outline guides, links, tags, inline code, reference cards and navigation. Not established by the images: mark highlights, text/block selection behavior, settings-specific states or cross-platform rendering. The official manifest checker and a separate Chromium fixture cover format, token application, mode switching and specified color combinations; they do not replace application-level validation of every state.

The old nord-light-fallback.png belongs to the historical 0.1.1 dark-only package. It is not used in the current README or manifest.

For every later Prism theme, supply a complete light and dark palette, then request real screenshots of both. Keep the same public sample page, window size, zoom, scroll position and expanded blocks. Leave editing mode and clear selection. If the source reference has only one mode, independently adapt the other and disclose the distinction. Synthetic fixture images must not be presented as application screenshots.
