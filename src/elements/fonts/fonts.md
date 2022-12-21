{{ this.package.nice }} uses the open license web font <a target="_blank" rel="noopener nofollow" href="https://public-sans.digital.gov/">Public Sans</a>, created and provided by the <abbr title="The U.S. Web Design System">USWDS</abbr> team. It is imported via <a target="_blank" rel="noopener nofollow" href="https://fonts.google.com/specimen/Public+Sans">Google Fonts</a>.

---

There are two token slots available for two different font faces, `primary` and `secondary`. However, having a different font for the secondary token is optional.

Token     | Font&nbsp;Family                   | Description
----------|------------------------------------|-
Primary   | {{ this.tokens.fontFace-primary }} | Designated for headings and some user interface typography.
Secondary | {{ this.tokens.fontFace-primary }} | Designated for buttons and body copy (lists/paragraphs).
