# readme-repo

[百度](https://www.baidu.com)

## 搜索跳转页（GitHub Pages）

[打开搜索跳转页 →](https://yexuanhs.github.io/readme-repo/)

页面内容：百度 / 必应两个搜索源切换，输入框输入什么就跳转什么，另外提供安卓 `intent://` 一键打开系统设置（含 WLAN、应用列表、电池优化）。

## 关于 intent 链接

GitHub 会把 `intent://` 直接过滤掉，不渲染成链接（实测原写法只剩纯文本，没有超链接样式），所以 README 里只能写 URL 编码版：

[打开系统设置](intent%3A%2F%2Fsettings%2F%23Intent%3Bscheme%3Dandroid.settings%3Bend)

要真正触发 intent，得用上面那个 Pages 页面里的按钮——它靠 JS 建 iframe 触发，不受 Markdown 过滤器限制。
