# RomBench.css
RomBench 的 CSS 框架，基于 Material Design 2，且对 Electron 做出了特别适配。
建议搭配 [MDUI](https://www.mdui.org/) 使用。
## 样式
### 暗色模式自适应
RomBench.css 支持在 macOS 和 Windows 的系统颜色模式调为暗色时，自动将内容调整为暗色。您可以通过添加类 ``rombench-main`` 和 ``rombench-content`` 来启用它。如需全局启用，请把该类添加到 body 上。
### Electron
RomBench.css 为 Electron 做出了特别适配，可以在无边框的 Electron 程序上快速完成应用栏的开发。在应用栏上添加 ``rombench-electron-appbar`` 一类，可以让您的应用栏获得以下特性：
* 按住鼠标可拖动
* 双击最大化

但需要注意的是：如果您的应用栏上有按钮或其他点击交互，请再为它们加上 ``rombench-electron-btn`` 一类，否则它们将无法被点击。
### 字体
RomBench.css 在西文字体中采用了 Google Sans，您可以通过添加类 ``rombench-md2-font`` 来启用它。如需全局启用，请把该类添加到 body 上。
## 组件
### 按钮
Rombench.css 为按钮提供了 5px 的圆角，您可以通过添加类 ``rombench-md2-btn`` 来启用它。如需获得更佳效果，建议与 ``mdui-btn`` 和 ``mdui-btn-raised`` 搭配使用。
### 菜单
RomBench.css 为 MDUI 的菜单提供了 5px 的圆角，您可以通过添加类 ``rombench-md2-menu`` 来启用它。
### 对话框
RomBench.css 为 MDUI 的对话框提供了 8px 的圆角，您可以通过添加类 ``rombench-md2-dialog`` 来启用它。
### 卡片
RomBench.css 为卡片提供了 8px 的圆角，您可以通过添加类 ``rombench-md2-card`` 来启用它。需获得更佳效果，建议与 ``mdui-card`` 或 ``mdui-shadow-[1-24]`` 搭配使用。
## 开发进度
- [ ] 独立菜单
- [ ] 独立对话框
- [ ] 独立卡片
- [ ] 独立按钮
- [ ] 不同大小的圆角
