# Atlantic 双语文章 -> 排版 PDF

由两份中英双语对照 Markdown 渲染生成的高质量 PDF（A4，含封面、页码、中英对照配色）。

## 文件

| PDF | 页数 | 大小 |
|---|---|---|
| what_we_really_know_bilingual.pdf | 12 | 986,823 B |
| russia_truth_about_plague_death_bilingual.pdf | 12 | 1,010,279 B |

## 渲染工具链

- Markdown -> 自写解析器 -> HTML -> weasyprint 70.0
- 字体：Noto Serif CJK SC / Noto Sans CJK SC（中文正文与标题），Liberation Serif（英文正文）
- 全部字体子集内嵌进 PDF（embedded=True），无豆腐块

## 版式

- A4，页边距 20/18mm，页眉 + 页码「第 N 页 / 共 M 页」
- 封面：深蓝渐变，英文标题 + 中文标题
- 正文：11.5pt / 行高 1.68
- 段落小标题「第 N 段」：浅蓝底 + 左侧蓝色竖条
- 英文引用块：浅灰底 + 灰色左边框
- 中文引用块：浅蓝底 + 蓝色左边框

## 视觉核对

proof/ 目录为首页/正文页的 PNG 截图（150 dpi）。
