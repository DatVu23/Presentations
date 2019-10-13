@snap[north span-100 text-pink]
Media Queries Syntax
@snapend

@snap[midpoint text-10]
```html zoom-20
    <link rel="stylesheet" media="screen and (color)" href="main.css" />
```
```css
    @import url(color.css) screen and (color);
```
@snapend

@snap[south span-100]
@[1-1]
@[2-2]
@snapend

---?

@snap[north span-100 text-pink]
Media Queries Syntax
@snapend

@snap[west span-50 text-10]
```css
    @media all and (min-width:500px) { … }
    @media (min-width:500px) { … }
```
@snapend

@snap[east span-50 text-10]
```css
    @media (orientation: portrait) { … }
    @media all and (orientation: portrait) { … }
```
@snapend