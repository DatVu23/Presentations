@snap[north span-100 text-pink]
Media Queries Width
@snapend

@snap[midpoint text-10]
```html
    <link rel="stylesheet" media="print and (min-width: 25cm)" href="http://…" />

```
```css
    @media screen and (min-width: 400px) and (max-width: 700px) { … }

```
```css
    @media handheld and (min-width: 20em), 
        screen and (min-width: 20em) { … }
```
@snapend