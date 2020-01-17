# Sass(Syntactically Awesome StyleSheets)
```
Sass是一款强化CSS的辅助工具，它在CSS语法的基础上增加了变量 (variables)、
嵌套 (nested rules)、混合 (mixins)、导入 (inline imports) 等高级功能，
这些拓展令 CSS 更加强大与优雅。使用 Sass 以及 Sass 的样式库（如 Compass）有助于更好地组织管理样式文件，以及更高效地开发项目。
```
## 特色功能(Features)
+ 完全兼容 CSS3

+ 在 CSS 基础上增加变量、嵌套 (nesting)、混合 (mixins) 等功能

+ 通过函数进行颜色值与属性值的运算

+ 提供控制指令 (control directives)等高级功能

+ 自定义输出格式

## 语法格式 (Syntax)
**Sass 有两种语法格式。首先是 SCSS (Sassy CSS) —— 也是本文示例所使用的格式 —— 这种格式仅在 CSS3 语法的基础上进行拓展，所有 CSS3 语法在 SCSS 中都是通用的，同时加入 Sass 的特色功能。此外，SCSS 也支持大多数 CSS hacks 写法以及浏览器前缀写法 (vendor-specific syntax)，以及早期的 IE 滤镜写法。这种格式以 .scss 作为拓展名。**

**另一种也是最早的 Sass 语法格式，被称为缩进格式 (Indented Sass) 通常简称 "Sass"，是一种简化格式。它使用 “缩进” 代替 “花括号” 表示属性属于某个选择器，用 “换行” 代替 “分号” 分隔属性，很多人认为这样做比 SCSS 更容易阅读，书写也更快速。缩进格式也可以使用 Sass 的全部功能，只是与 SCSS 相比个别地方采取了不同的表达方式，具体请查看 the indented syntax reference。这种格式以 .sass 作为拓展名。**

**任何一种格式可以直接 导入 (@import) 到另一种格式中使用，或者通过 sass-convert 命令行工具转换成另一种格式：**
```
# Convert Sass to SCSS
$ sass-convert style.sass style.scss

# Convert SCSS to Sass
$ sass-convert style.scss style.sass
```
## 使用 Sass (Using Sass)
+ [1.1-Sass本地环境搭建及测试使用](https://github.com/shanecss/Sass/blob/master/1.1-Sass%E6%9C%AC%E5%9C%B0%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA%E5%8F%8A%E6%B5%8B%E8%AF%95%E4%BD%BF%E7%94%A8.md)
+ [2.1-Sass教程：变量和嵌套CSS规则](https://github.com/shanecss/Sass/blob/master/2.1-Sass%E6%95%99%E7%A8%8B%EF%BC%9A%E5%8F%98%E9%87%8F%E5%92%8C%E5%B5%8C%E5%A5%97CSS%E8%A7%84%E5%88%99.md)