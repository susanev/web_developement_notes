# HTML5 Notes

## Structure

### HTML sections and outlines
* sections followed by headings define outline
* heading followed by heading creates implicit section including the second heading
* blockquote, details, fieldset, figure, and td are all sectioning roots and headings inside of them are not included in the outline
* aside and nav (can have multiples) are not included in outline
* header and footer tags can represent the header and footer of any/all sections; they do not create new sections in the outline
* non-HTML5 browsers will display them as inline by default so use below css  
  `section, article, aside, footer, header, nav, hgroup {   
   display:block;   
   }`
* ugh IE9, check source for more details
* Source: [MDN: Using HTML sections and outlines](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Using_HTML_sections_and_outlines)
