# juejin-book-downloader

掘金小册简易下载脚本。

## 使用方法

在掘金某本小册或小册的某篇文章的页面打开控制台，输入

```js
var script = document.createElement('script');
script.src = 'https://harrisoff.github.io/static/js/juejin-book-downloader.js';
document.body.appendChild(script);
```

然后执行 `main()`