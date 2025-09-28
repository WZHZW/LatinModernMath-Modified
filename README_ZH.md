# LatinModernMath-Modified

本仓库提供 [Latin Modern Math](https://www.gust.org.pl/projects/e-foundry/latin-modern) 字体的**修改版本**，旨在解决一个核心痛点：在 Microsoft Word 中获得与 LaTeX 一致的公式显示效果。

原始字体由 **GUST e-foundry** 开发，并基于 **GUST 字体许可证 (GFL)** 发布。

---

## 🎯 解决的问题

标准的 *Latin Modern Math* 字体在 LaTeX 环境中表现完美，但在 Microsoft Word 的公式编辑器中，其**双线大写字母**（例如，表示实数集的 `\mathbb{R}`，即 ℝ）的渲染效果却不尽人意，无法呈现出 LaTeX 用户（例如使用 `amssymb` 宏包）所习惯的那种清晰、经典的“空心”样式。

**本修改版字体正是为了解决这一问题。** 它确保了在 Word 公式编辑器中输入的双线字母也能拥有专业 LaTeX 文稿中的视觉效果。

## 🔧 修改内容

与官方的 *Latin Modern Math* 字体相比，此版本包含一项核心改动：

- **优化的双线字形**: 将**双线大写字母 (`\mathbb{}`)** 的字形替换为视觉效果更佳的 MSBM 风格，确保其在 LaTeX 和 Microsoft Word 中拥有一致且专业的外观。
- **兼容性微调**: 进行了一些次要调整，以提升在数学排版中的兼容性。

![picture](/picture.png)

<p align="center"> 图：修改前后\mathbb{}样式的对比 </p>

除上述修改外，所有其他字形和字体特性均与原始版本保持一致。

## 📜 许可证

- 本字体仍然基于 **GUST 字体许可证 (GFL)** 进行许可。
- 您可以根据相同的条款自由使用、修改和分发本字体。
- 原始版权归 **GUST e-foundry** 所有。
- 此修改版本在分发时不提供**任何担保**。

有关详细信息，请参阅本仓库中包含的 [LICENSE](LICENSE) 文件。

## 🙏 致谢

- **原始作品**: [GUST e-foundry](https://www.gust.org.pl/projects/e-foundry)
- **许可证**: [GUST 字体许可证](http://www.gust.org.pl/projects/e-foundry/licenses)
