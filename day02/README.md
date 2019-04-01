## Day 02 - 学习 HTML 基础知识

HTML（HyperText Markup Language）是一种用于创建网页的标准标记语言。

### 常见标签

- html - Html 根标签（根结点）
- head - 文档描述头标签
- title - 文档标题标签
- body - 文档可见部分根标签
- h1 ~ h6 - 标题
- div - 布局
- p - 段落
- a - 链接
- img - 图片
- ul - 无序列表根节点
- ol - 有序列表根节点
- li - 列表子节点

### 基本语法

所有标签成对出现，意思是每个标签都有开始标签和结束标签，开始标签存在于一对尖括号（`<>`）中，结束标签除了尖括号之外，需要在第一个尖括号后加入`/`字符。

开始标签和结束标签之间是该标签的子节点（嵌套内容），如果不需要子节点，可以单标签关闭，类似 `<br />` 或 `<img src="image.png" />`

每个标签都具有语义，大部分标签可嵌套。

#### 例：

```html
<!-- html begin -->
<html>
  <!-- head begin -->
  <head>
    <title>Page Title</title>
  </head>
  <!-- head end -->

  <!-- body begin -->
  <body>
    <!-- visible part begin -->
    <h1>heading 1</h1>

    <p>paragraph...</p>

    <ul>
      <li>list item 1</li>
      <li>list item 2</li>
      <li>list item 3</li>
      <li>
        <a href="https://url">link</a>
      </li>
    </ul>
    <!-- visible part end -->
  </body>
  <!-- body end -->
</html>
<!-- html end -->
```

👆 文件地址： [demo.html](./demo.html)
