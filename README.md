# GGUI

## 技术流

- ES6
- CSS3
- Webpack
- LESS

## 设计思想

根据业务和高保真的不同设计，可配置不同模块的呈现方式，支持新加入不同的插件。

- 模块化
- 可配置
- 插件化

## 业务逻辑

通过改变不同的theme输出不同样式的uikit。具体实现方式：
有一个 `inputs` 文件夹，里面每一个 `css` 文件对应一个新的 `uikit`，具体的交互在 `modules` 文件夹中编写，例如其中的 `button` 文件夹专门写按钮的交互。像日历插件、表单验证插件、文件上传插件等，这些写在 `plugins` 文件夹中。最终输出的 `uikit` 在 `outputs` 中。

- inputs
- modules
- plugins
- outputs
- docs
- website