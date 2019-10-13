@snap[north span-100 text-pink]
Media Feature Aspect-Ratio
@snapend

@snap[midpoint text-10]
```css
    /* Minimum aspect ratio */
@media (min-aspect-ratio: 8/5)  { ... }

/* Maximum aspect ratio */
@media (max-aspect-ratio: 3/2) { ... }

/* Exact aspect ratio, put it at the bottom to avoid override*/
@media (aspect-ratio: 1/1)  { ... }
```
@snapend