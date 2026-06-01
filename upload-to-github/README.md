# 进货利润速算

一个可以部署到 GitHub Pages 的 NZD 进货利润计算小网页。输入不含 GST 的进货价后，会按固定 GST 15% 换算成本，并可按“一瓶价格”、“一箱 6 瓶”或“一箱 12 瓶”换算成单瓶成本。拖动毛利率滑杆后，页面会实时显示建议单瓶售价；也可以输入当前卖价，反算真实毛利。

## 发布到 GitHub Pages

1. 在 GitHub 新建一个仓库，例如 `profit-calculator`。
2. 上传本文件夹里的所有文件。
3. 进入仓库 `Settings` -> `Pages`。
4. `Source` 选择 `Deploy from a branch`。
5. `Branch` 选择 `main`，目录选择 `/root`，保存。
6. 等一两分钟后，GitHub 会给出一个网址，例如：

```text
https://你的用户名.github.io/profit-calculator/
```

手机和电脑都可以打开这个网址。手机浏览器里可以选择“添加到主屏幕”，之后就像小程序一样打开。
