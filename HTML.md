# Awesome HTML

- 每个标签应该另起一行
- 每个属性应该另起一行，并保持对齐 (可以与第一个属性对齐，也可以另起一行缩进两格对齐）
- 属性的顺序：class 最前，type 其次

```html
<input class="form__input"
       type="text">
```
- 被标签包裹的文字可以考虑独占一行

```html
<a class="u-link"
   href="${render_url(topic.get_url(), location=location)}"
   target="_blank">
  话题：${topic.name}
</a>
```
