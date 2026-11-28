![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Domain: PC Cooling](https://img.shields.io/badge/Domain-PC%20Cooling-blue)
![Status: Hardware Concept](https://img.shields.io/badge/Status-Hardware%20Concept-orange)

**[🇬🇧 English](README_EN.md) | [🇨🇳 简体中文](README.md)**

# RGB-Shift-Fan
正叶风扇“平移”发光技术开源 | Shifting RGB to the rear frame for 100% airflow.


> **💡 设计原则 (Core Principle)**
> **“既然正叶风扇翻装后无法透光，那就将光源直接移至背面外框。”**
> *(Since a standard pull-fan hides the RGB when flipped, shift the light to the rear frame.)*


## 📝 项目声明 (Notes)

1. **关于语言与表达 (About Language)**：
   本项目主理人母语为中文。英文 README 由翻译工具辅助生成，如有术语不准确或表述不清之处，敬请谅解，欢迎提交 PR 指正。

2. **关于开源授权 (License)**：
   本项目已采用 MIT 协议完全开源。欢迎任何形式的 DIY、修改及商业量产，但请务必遵守协议保留原作者署名。

3. **关于其他平台 (Other Platforms)**：
   首发手稿及动态在酷安与 CSDN，完整链接见文末或评论区。全网同名/同人，欢迎查证防伪。

   ---

## 📖 项目背景 (The Problem)

在 PC DIY 领域，玩家为了机箱底部或侧面的进风，经常面临两难选择：

1. **购买反叶风扇**：为了保证玩家能看到 RGB，反叶风扇在流体力学上做了大量妥协，导致风压和风量远低于同价位正叶风扇，且价格昂贵（反叶税）。
2. **正叶风扇翻装**：虽然保住了满血性能，但背面是丑陋的电机十字支架，不仅看不到灯光，还极其破坏机箱美感。
   *(注：市面上少量的“双面发光风扇”虽然能解决，但价格极其高昂。)*

## 🛠️ 核心方案：平移技术 (The Solution)

本设计利用极简的**“平移”**思维，不改变任何气动结构与电机支架：

* **空间平移**：将原本在正面的灯带/导光条，直接平移嵌入至外框的背面端面（出风侧）。
* **技术平移**：100% 复用现有的 FPC 走线、乳白均光板、贴片灯珠等成熟供应链技术，只需在现有正叶模具上微调开槽，成本极低。

## 🚀 工程优势 (Engineering Advantages)

* 🌪️ **零气动干涉**：灯带隐藏在外框死角，不阻挡任何气流，风压风量 100% 满血。
* 🛡️ **绝对结构安全**：完美避开电机支架的高震动受力区，杜绝共振形变与断轴风险。
* 💰 **极低量产成本**：量产零售价可压至几十元，让玩家用最便宜的价格享受顶级体验。

*⚠️ **免责声明 (Disclaimer)**：此 3D 渲染图/手绘图仅供直观展示“平移”理论的结构逻辑，未经任何流体力学测试与物理打样验证。本人并非专业建模师，强烈不建议任何人直接基于此图进行实物开模，若您执意尝试导致硬件损坏，本人概不负责。*
