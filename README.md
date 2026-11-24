# tabata-exercise-images

Public image host for custom workouts in Tabata Timer (`com.evgeniysharafan.tabatatimer`).
App-facing URLs use the jsDelivr CDN pinned to a commit, `web/` = 1280px JPEG previews
(33–70 KB, mobile-friendly); root PNGs are the full-size masters:

```
https://cdn.jsdelivr.net/gh/wangnszh/tabata-exercise-images@<commit>/web/<name>.jpg
```

`raw.githubusercontent.com` is unreliable from mainland China networks (intermittent
timeouts, measured 2026-11-21); jsDelivr measured ~1 s for the JPEGs. Fallback edge:
`gcore.jsdelivr.net` (same path).

| file | 动作 | 说明 |
| --- | --- | --- |
| cat_cow.png | 猫牛式（瑜伽） | 左猫右牛，脊柱拱/塌对比 |
| scap_pushup.png | 肩胛俯卧撑 | 直臂平板，实/虚影对比肩胛前伸后缩 |
| scap_pullup.png | 肩胛引体 | 直臂悬垂，耸肩放松位 vs 下压发力位 |
| band_side.png | 弹力带双臂+躯干体侧 | 踩带双手握端，侧向伸展 |
| scap_band_kneeling.png | 跪姿弹力带肩胛提拉 | 跪垫双手握高位锚点弹力带，橙色箭头示意肩胛驱动下拉与缓慢回放 |
| scap_updown.png | 上下活动肩胛骨 | 肩胛上提/下压，双向箭头 |
| shoulder_circle_front.png | 前绕肩 | 向前→上→后→下画圈 |
| shoulder_circle_back.png | 后绕肩 | 向后→上→前→下画圈 |
| scap_shake.png | 跳动抖动肩胛骨 | 放松小跳抖动收尾 |

Notes:
- 除泡沫轴滚背（另用 somasystem.com 实物照片）外，本仓图片均为 **AI 生成示意图**（右下角带平台「AI生成」标识），已逐张目检动作与箭头方向；仅供个人训练参考，不构成医疗或教练建议。
- Images are AI-generated schematic illustrations, visually checked for pose and arrow direction. Personal-use reference only.