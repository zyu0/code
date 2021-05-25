### XML

- 设计为传输和存储数据，其焦点是数据的内容
- 自行定义标签和文档结构
- 是对HTML的补充

	- 可将数据从HTML中分离，独立存储，让HTML专注于布局和显示，确保底层数据不需要修改HTML
	- 通过JavaScript来读取XML，更新HTML

### HTML

- 设计用来显示数据，其焦点是数据的外观
- 标签和结构是预定义的



**在 HTML，经常会看到没有关闭标签的元素：**

```html
<p>This is a paragraph
<p>This is another paragraph
```

**在 XML 中，省略关闭标签是非法的。所有元素都*必须*有关闭标签：**

```xml
<p>This is a paragraph</p>
<p>This is another paragraph</p>
```