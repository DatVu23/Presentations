@snap[north span-100 text-pink]
Media Queries Rules Definition
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

---?LOGICALEXPRESSION.md

---?

@snap[north span-100 text-pink]
Media Queries Rule List
@snapend

@snap[midpoint text-10]
```css
    @media screen and (color), projection and (color) { … }
```
@snapend


---?

@snap[north span-100 text-pink]
Media Queries Not Keyword
@snapend

@snap[midpoint text-10]
```html
    <link rel="stylesheet" media="not screen and (color)" href="main.css" />

```
```css
    @media not screen and (color) { ... }
```
@snapend


---?

@snap[north span-100 text-pink]
Media Queries Only Keyword
@snapend

@snap[midpoint text-10]
```html
    <link rel="stylesheet" media="only screen and (color)" href="main.css" />
    
```
```css
    @media only screen and (color) { ... }
```
@snapend


---?

@snap[north span-100 text-pink]
Media Queries Device-Aspect-Ratio
@snapend

@snap[midpoint text-10]
```html
    <link
        rel="stylesheet"
        media="aural and (device-aspect-ratio: 16/9)" 
        href="main.css"
    />
```
@snapend


---?

@snap[north span-100 text-pink]
Media Queries Speech Devices
@snapend

@snap[midpoint text-10]
```html
    <link
        rel="stylesheet"
        media="speech and (min-device-width: 800px)" 
        href="main.css"
    />
```
@snapend



