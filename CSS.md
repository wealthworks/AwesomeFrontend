# Awesome CSS

- http://philipwalton.com/articles/css-architecture/
- 借鉴一些 [ITCSS](https://speakerdeck.com/dafed/managing-css-projects-with-itcss) 的思想
- 在 component 层只使用 class selector
- CSS class 的命名采用 [BEM](https://css-tricks.com/bem-101/)，如 `.block_element--modifier`
- utility 和 state class 的命名借鉴 [SUIT CSS](https://github.com/suitcss/suit/blob/master/doc/README.md)，如 `u-left`，`is-active`
- 会在 js 中被 select 的 class 需要加 `js-` prefix，如 `js-submit-button`。在 `js-` class 上不加样式
