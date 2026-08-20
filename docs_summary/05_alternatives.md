# 同类方案与 2.0 观感

## 和 Lumina 同赛道

| 方案 | 开源 | 特点 |
|------|------|------|
| [HueForge](https://shop.thehueforge.com/pages/about-hueforge) | 闭源付费 | TD 预测叠色；默认可出 STL + 换色说明；3MF 需第三方插件 |
| [AutoForge](https://github.com/hvoss-techfak/AutoForge) / FlatForge | 开源 | 自动优化叠层；朝下薄板 |
| [Kromacut](https://github.com/vycdev/Kromacut) | 开源 | 浏览器，Beer-Lambert / TD 路线 |
| ColorStack 等 | 多为网页/闭源 | 背光 CMYK 灯片或平面叠色 |
| Lumina 1.x | GPL 开源 | **拍照校准 LUT**，少理论猜色 |

叠色原理并非 Lumina 首创；HueForge 等是更早的商业标杆。Lumina 热度一般，不代表工艺无人做。

## HueForge 操作要点

- 功能在官网客户端，不是 GitHub 主仓  
- 默认 **不** 内置 3MF；[3MF 插件](https://shop.thehueforge.com/products/3mf-plugin) 另购  
- 比 Lumina 更偏手调 TD/层序，学习曲线不低  

## 关于 2.0

付费内测体感「堆功能、核心没变」与官方表述一致：2.0 重写 UI/工作流/架构，叠色仍是透光层叠；主打梯度卡 + 计算模拟减校准负担，不是换一门全彩物理。

FDM 天花板（离散料、换色、肤色渐变）2.0 也消不掉。

## 自研取向

若需求是固定机型、固定耗材、人像先 stylize、少选项、背板链路自洽——基于核心算法自做工具合理，不必等官方大版本。先做最小闭环，再按题材加 6 色等。
