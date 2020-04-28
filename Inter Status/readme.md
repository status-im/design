# Inter Status

This is a fork of the open source Inter font, designed by Rasmus Andersson

For context, at Status we use Inter exclusively in our mobile apps. However by default, Inter doesn't come with glyphs designed for disambiguation like a slashed zero or uppercase i. Those features are available through OpenType character substitution, something which is unfortunately unavailable to control with React Native. Because of that and the need to display Ethereum addresses with no doubt of characters used, we include our own version that has those features enabled by default.

---

Changed:
- Slashed zero enabled by default
- Uppercase i uses alternate design with horizontal slabs by default
- Lowercase l uses an alternate design with curved tail by default
- Disabled the contextual alternates rule where the x character would be substituted with multiply glyph whenever joined by two digits
- Copyright glyph is replaced with the SNT token symbol :)

Original design:
https://rsms.me/inter/
