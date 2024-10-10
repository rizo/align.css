# align.css

**Demo**: https://rizo.github.io/align.css/

Natural, consistent, memorable CSS classe for aligning things in CSS.

## Installation

Just put this in your CSS file:

```css
/* Container */
.row { display: flex; flex-direction: row;    }
.col { display: flex; flex-direction: column; }

/* Align */
.row.left,   .col.top    { justify-content: flex-start; }
.row.center, .col.middle { justify-content: center;     }
.row.right,  .col.bottom { justify-content: flex-end;   }
.row.top,    .col.left   { align-items: flex-start;     }
.row.middle, .col.center { align-items: center;         }
.row.bottom, .col.right  { align-items: flex-end;       }

/* Justify */
.row.between, .col.between { justify-content: space-between; }
.row.even,    .col.even    { justify-content: space-evenly;  }
.row.around,  .col.around  { justify-content: space-around;  }
```
