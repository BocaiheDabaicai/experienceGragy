## 笔记

---

#### 一. 解析图片

存在两种方式

1. `js`，通过预先设置DOM元素添加图片位置，实现打包渲染图片

2. `css`，通过预先设置`background`属性渲染图片到界面上，实现打包渲染图片

相关代码如下

```js
// js
import Icon from './icon.png'

const myIcon = new Image();
myIcon.src = Icon;
element.appendChild(myIcon);


// css
```
