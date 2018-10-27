---
title: Specify How Fonts Should Degrade
---
## Specify How Fonts Should Degrade

The fisrt challenge is to apply the apply the `monospace` font to the `h2` element:
to do so the line number 8 in the h2 element:

```css
  h2 {
    font-family: Lobster;
  }
```
becomes:
```css
  h2 {
    font-family: Lobster, monospace;
  }
```
In this way the font `Lobster` will be the first choice, but if it is not avaiable the `monospace` will replace it.

Then we have to comment out the first line (the `Link` tag ) which import of the `Lobster`, using `<!--` `-->` so it becomes:

```html
<!--  <link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css"> -->
```

In this was since `Lobster` is not longer imported the `monospace` will replace it. 
