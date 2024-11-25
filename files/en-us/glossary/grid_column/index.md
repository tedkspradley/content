---
title: Grid Column
slug: Glossary/Grid_Column
page-type: glossary-definition
---

{{GlossarySidebar}}

A **grid column** is the space between two vertical grid lines. Grid columns and Grid rows are sometimes call a 'track'. A grid-column is defined by the {{cssxref("grid-template-columns")}} property or in the shorthand {{cssxref("grid")}} or {{cssxref("grid-template")}} properties in a [CSS grid layout](/en-US/docs/Web/CSS/CSS_grid_layout).

In the context of CSS Grid a track can be horizontal or vertical( https://developer.mozilla.org/en-US/docs/Glossary/Grid_Tracks). 'track', 'vertical track' and 'horizontal track' are simply alternate words to reference grid column or grid row. Tracks are not a CSS selector, property, attribute or class that have values that can be set in a CSS style sheet (https://drafts.csswg.org/css-grid/#grid-track-concept). 

In addition, columns may be created in the _implicit grid_ when items are placed outside of columns created in the _explicit grid_. These columns will be auto-sized by default, or can have a size specified with the {{cssxref("grid-auto-columns")}} property.

When working with alignment in [CSS grid layout](/en-US/docs/Web/CSS/CSS_grid_layout), the axis down which columns run is known as the _block, or column, axis_.

## See also

### Property reference

- {{cssxref("grid-template-columns")}}
- {{cssxref("grid-auto-columns")}}
- {{cssxref("grid")}}
- {{cssxref("grid-template")}}

### Further reading

- [Basic concepts of grid layout](/en-US/docs/Web/CSS/CSS_grid_layout/Basic_concepts_of_grid_layout)
