# Adaptation notes

## Provenance

Nord upstream: https://github.com/nordtheme/nord, revision `1cef71605416a222e57225b544540ce0fcec18d4`, MIT, Sven Greb. The package is a behavioral palette adaptation, not a CSS port. The initial local reference was Codex's dark Nord preset; its visual surface/text roles informed the adaptation. No Codex program code or assets are distributed.

## Public API boundary

Only the 21 color tokens accepted by Tine Theme API 0.2 are included. The earlier custom.css prototype also set auxiliary muted text, settings typography, scrollbar, task marker, hover and focus rules. Those rules are not accepted by the package allowlist and are intentionally absent. No claim is made that the JSON package reproduces every prototype detail.

The dark palette maps canvas, sidebar, elevated surfaces, text, links, tags, guides, bullets, selection, inline code and amber marks to semantic roles. Tine generates the bounded CSS. Other roles retain host behavior; custom.css and device accent preferences may affect the outcome.

## Modes

Both light and dark are explicitly defined with all 21 supported tokens. The dark mapping is unchanged from 0.1.1. The light palette is a Prism adaptation using Nord Snow Storm surfaces and Polar Night text, with darker blue/violet accents for text readability; it is not a native Codex light preset. Prior light fallback screenshots are historical only and must not be used to advertise the new light palette. Real Windows light and dark screenshots were supplied after installing the dual-mode package and are displayed in both READMEs.

## Versioning

0.1.0 was a local preview named Nord for Tine. 0.1.1 is the first public Prism package; the stable ID is retained. Tine identifies installed versions by id@version, so future manifest changes need a new version.

0.2.0 adds the complete light palette. The stable package ID remains unchanged. The immutable 0.1.1 release remains available as a historical dark-only version; 0.2.0 is a separate dual-mode release.

## Local 0.2.0 checks

The official manifest checker passes. A Chromium fixture using Tine's cached CSS verified the complete 21-token palette in both modes and a light → dark → light switch. Dark tokens are unchanged from 0.1.1. Measured light-canvas contrasts: body 8.73:1, links 5.92:1, tags 6.02:1; inline code 7.45:1, mark 8.71:1 and selected body 7.71:1 on their respective surfaces. These are scoped fixture results, not full application or cross-platform acceptance.

The retained dark tag color measures 4.41:1 on its main background, so no all-text AA claim is made. Real new light and dark screenshots were supplied for the 0.2.0 release; unpictured interactions still require application-level checks as needed.
