# 你比划我猜 · 旋转感应 Demo

## 运行
最简单：直接打开 index.html，可以测试界面和按钮。

## 真机旋转传感器测试
设备方向 API 在现代浏览器中通常需要安全上下文，建议通过 HTTPS 部署。
可把 index.html 放到任意静态站点托管服务。

## 操作
- 向前倾：猜对
- 向后倾：跳过
- 自定义题库：每行一道题，保存在 localStorage
- 电脑测试：使用“猜对 / 跳过”按钮

## 调参
index.html 中：
- THRESHOLD = 28：触发角度
- RELEASE_ZONE = 12：回中立区解锁范围
- COOLDOWN_MS 当前仅保留作扩展
