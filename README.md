# Accessible page for content

Used HTML5 Boilerplate for template

Removed header, footer, aside, nav

Removed sectioning elements (section, article)

Removed unused CSS classes

Defined main content width for readability on desktop (under 80 character width for AAA)

Font size set in em, responsive (passes text-resizing to 200% AA)

Used headings with blockquotes for physical instructions e.g. panel on left wall (unsure if this is the best approach but makes sense as the instruction is quoting what is there physically)

Question about special charaters e.g. | no treatment added as not enough information about their purpose and usage.

------------------

#Update

Additional content added

Restructured markup for better semantics:
- article element for whole document
- section elements for panels and nested sections for labels
- figure and figcaption for labels of physical objects
- changed physical directions e.g. panel on left wall from headings to strong (before section)
