# 空间坐标系 · 交互讲解

在线页面：https://jctaylor666.github.io/coordinate-systems/

从"同一个点有两套坐标"讲起，经过旋转矩阵、齐次坐标、欧拉角、体素与世界坐标、相机外参 c2w / w2c、投影、DRR 射线采样，一直讲到 C 臂（DiffDRR / GeoReg）和 R2-Gaussian 的相机与投影。每一章都有可以拖动的交互和一道小题；打开页面时会自动跑一组数值自检（右上角"自检"可展开）。

- 单个 `index.html`，没有构建步骤；本地直接用浏览器打开即可。
- 3D 部分从 jsDelivr 加载 three.js r128，需要联网；文字、矩阵数字和 2D 图离线也能用。
- 模拟的"头"和所有数值都是示意，不是真实数据。
- 访问统计用 GoatCounter（不用 cookie，只记页面加载和来源），看板：https://jctaylor666.goatcounter.com 。本地打开 `index.html` 时不计数。
