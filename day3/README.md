# Day 3 - CSS

## Inline css

```html
<h5 style="color:red">text</h5>
```

## Style tag

```html
<html>
  <header>
    <style>
      h5 {
        color: red;
      }
    </style>
  </header>
  <body>
    <h5>text</h5>
  </body>
</html>
```

## Stylesheet file

```html
<html>
  <header>
    <link rel="stylesheet" href="mystyle.css" />
  </header>
</html>
```

Define `mystyle.css` somewhere separately

```css
h5 {
  color: red;
}
```
