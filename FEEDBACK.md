# Paris family page feedback

## 2026-06-25 01:40 PDT — Desktop overflow in choice cards

Source screenshot: `/home/padraig/.hermes/profiles/forge/image_cache/img_e832c5109d15.png`

User note: desktop view has serious overflow issues. Do not fix immediately; carry this into the feedback queue.

Observed issue:
- Two-column card layout is overflowing/clipping horizontally on desktop.
- Right-hand cards are cut off by the viewport/container edge.
- Card titles and body text are clipped, e.g. Monday second card and Tuesday second card.
- Pill/tag rows also run into the clipping area.
- This affects the Monday and Tuesday choice sections and makes the page feel broken/confusing on desktop.

Required later fix:
- Treat as part of the layout polish pass, not the current feedback discussion.
- Desktop card grid must fit within the right column without clipping.
- Long card titles, descriptions, taglines, and link pills must wrap cleanly.
- Verify at desktop widths as well as mobile.
