# 壁虎前端团队工具

本插件主要与 JS/TS/React/SCSS 相关，包含以下功能：

- SCSS 中 `px2vw` 自定义函数的支持
  - 对 SCSS 代码选中区域内的 px 值统一加上 px2vw() 调用
  ![px2vw-select-and-replace](https://raw.githubusercontent.com/heruns/bihu-fe-tools/main/demo/px2vw-select-and-replace.gif)
  - 在 SCSS 值中输入数字值或 `px2vw` 开头的值时智能提示
  ![px2vw-intellisense](https://raw.githubusercontent.com/heruns/bihu-fe-tools/main/demo/px2vw-intellisense.gif)
- 组件重命名
  - 一键替换文件名和文件内容
  ![component-rename](https://raw.githubusercontent.com/heruns/bihu-fe-tools/main/demo/component-rename.gif)
- 不仅生成代码片段，还会智能导入对应模块
  - `useState` 代码片段: `useState -bihu`
  ![use-state-intellisense](https://raw.githubusercontent.com/heruns/bihu-fe-tools/main/demo/use-state-intellisense.gif)
  - `useEffect` 代码片段: `useEffect -bihu`
  ![use-effect-intellisense](https://raw.githubusercontent.com/heruns/bihu-fe-tools/main/demo/use-effect-intellisense.gif)
- React 和 TS 代码片段
  - JSDoc 风格注释代码片段: `/** */ -bh`
  - className module 代码片段: `className module -bh`
  - 常量对象代码片段: `constant map -bh`
  - 常量 id 对象代码片段: `constant IdNameObj -bh`
  - Antd modal 二次封装代码片段: `antd modal init -bh`
  - img 代码片段: `img -bh`
- SCSS 代码片段
  - 快捷输入 `:global`: `:global -bh`
  - 快捷输入 `:global(.mobile)`: `:global(.mobile) -bh`

# Bihu Frontend Team Tools

This plugin is mainly related to JS/TS/React/SCSS and includes the following features:

- Support for the `px2vw` custom function in SCSS
  - Automatically add `px2vw()` function call to all px values in the selected area of SCSS code
  - Smart prompt for numeric values or values starting with `px2vw` in `:global(.mobile)` or `.isMobile` selectors
- Component renaming
  - One-click replacement of file names and file contents
- Smart import along with code snippet generation
  - `useState` code snippet: `useState -bihu`
  - `useEffect` code snippet: `useEffect -bihu`
- React and TS code snippets
  - JSDoc style comment code snippet: `/** */ -bh`
  - className module code snippet: `className module -bh`
  - Constant object code snippet: `constant map -bh`
  - Constant id object code snippet: `constant IdNameObj -bh`
  - Antd modal encapsulation code snippet: `antd modal init -bh`
  - img code snippet: `img -bh`
- SCSS code snippets
  - Shortcut for inputting `:global`: `:global -bh`
  - Shortcut for inputting `:global(.mobile)`: `:global(.mobile) -bh`
