Github’s fixed-width font stack was recently changed to

```css
pre, code, tt {
  font-family: Consolas, "Liberation Mono", Courier, monospace;
}
```

This unpacked Chrome extension simply resets the font of fixed-width elements to Menlo.

```css
pre, code, tt {
  font-family: Menlo;
}
```
