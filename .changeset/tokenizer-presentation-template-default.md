---
'@astryxdesign/cli': patch
---

[chore] The Tokenizer blocks and the table-inbox and work-item-detail page templates follow Tokenizer's `'adaptive'` default. On a compact touch screen they show the bottom sheet, and props the sheet does not render (`hasClear`, `endContent`, `tokenOverflowBehavior`, `hasEntriesOnFocus`, `renderToken`, `hasAutoFocus`) have no effect there. Pass `presentation="popover"` to keep the inline field on every device.

@imdreamrunner
