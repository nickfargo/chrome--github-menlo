Github’s fixed-width font stack was recently changed to

```css
pre, code, tt {
  font-family: Consolas, "Liberation Mono", Courier, monospace;
}
```

This unpacked Chrome extension simply pushes **Menlo** for fixed-width elements across all **github.com** domains.

```css
pre, code, tt {
  font-family: Menlo, Consolas, Courier, monospace;
}
```
