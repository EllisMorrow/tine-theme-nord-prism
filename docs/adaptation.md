# Adaptation notes

## Provenance

Nord upstream: https://github.com/nordtheme/nord, revision `1cef71605416a222e57225b544540ce0fcec18d4`, MIT, Sven Greb. The package is a behavioral palette adaptation, not a CSS port. The initial local reference was Codex's dark Nord preset; its visual surface/text roles informed the adaptation. No Codex program code or assets are distributed.

## Public API boundary

Only the 21 color tokens accepted by Tine Theme API 0.2 are included. The earlier custom.css prototype also set auxiliary muted text, settings typography, scrollbar, task marker, hover and focus rules. Those rules are not accepted by the package allowlist and are intentionally absent. No claim is made that the JSON package reproduces every prototype detail.

The dark palette maps canvas, sidebar, elevated surfaces, text, links, tags, guides, bullets, selection, inline code and amber marks to semantic roles. Tine generates the bounded CSS. Other roles retain host behavior; custom.css and device accent preferences may affect the outcome.

## Modes

Only dark is defined. No light palette was invented for the dark-only source reference. A light-mode screenshot records the host fallback and is kept outside the manifest's advertised theme screenshots. The underlying fallback theme was not recorded, so it is not identified as any specific preset.

## Versioning

0.1.0 was a local preview named Nord for Tine. 0.1.1 is the first public Prism package; the stable ID is retained. Tine identifies installed versions by id@version, so future manifest changes need a new version.
