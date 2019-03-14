## Day 01 - 了解 HTML、CSS、JavaScript 之间的关系

简单理解，HTMl、CSS、JavaScript 之间的关系就是：

- HTML - 描述页面结构、内容
- CSS - 控制页面布局、样式
- JavaScript - 页面逻辑与交互

查看如下三个页面在浏览器中的效果，然后查看代码对比差别：

```bash
# 在 terminal 中分别执行如下命令

# 查看效果：
open ./html.html
open ./html_css.html
open ./html_css_js.html

# 看过效果对比后，查看代码差别：
diff html.html html_css.html
diff html_css.html html_css_js.html

# 也可以用任何文本编辑器打开这三个文件查看
```

上面的命令会打开三个页面，分别是：

- html.html - 只包含 HTML 代码
- html_css.html - 相同的 HTML 代码，增加了 CSS 修改了一些样式
- html_css_js.html - 在上一个文件的基础上，增加了 JS 代码，显示一些动态效果

对比效果与代码差异，理解 HTML、CSS、JS 之间的关系。
