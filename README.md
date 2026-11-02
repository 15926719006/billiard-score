# 台球记分

三个人打台球用的记分页。单文件、离线可用、数据存本机。

打开：https:// 你的用户名.github.io/仓库名/

## 本地预览

```bash
python3 -m http.server 8765
# 浏览器打开 http://127.0.0.1:8765
```

## 说明

- `index.html` 是全部逻辑，不依赖任何外部资源
- `sw.js` 做离线缓存：首次打开后断网也能用
- 数据存在浏览器 localStorage，换设备或清缓存会丢
- 加到主屏幕（Safari 分享 → 添加到主屏幕）后是全屏应用

## 部署

仓库 Settings → Pages → Source 选 `Deploy from a branch`，分支 `main`，目录 `/ (root)`。
