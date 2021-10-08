# prism-themes

`prism-themes`의 테마를 브라우저 테마에따라 다른 모습으로 나타내기위해서 제작

```css
@media (prefers-color-scheme: light) {
  @import "https://hansanghyeon.github.io/prism-themes/themes/prism-ghcolors.min.css";
}
@media (prefers-color-scheme: dark) {
  @import "https://hansanghyeon.github.io/prism-themes/themes/prism-dracula.min.css";
}
```

```css
@import url('https://hansanghyeon.github.io/prism-themes/themes/prism-ghcolors.min.css') screen and (prefers-color-scheme: light);
@import url('https://hansanghyeon.github.io/prism-themes/themes/prism-dracula.min.css') screen and (prefers-color-scheme: dark);
```


Light Theme: GHColors
Dark Theme: dracula

## 사용방법

link 방식

```html
<link rel="stylesheet" type="text/css" href="https://hansanghyeon.github.io/prism-themes/main.css">
```

import 방식

```css
@import url('https://hansanghyeon.github.io/prism-themes/main.css');
```
