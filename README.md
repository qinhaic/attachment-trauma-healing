# 依恋、创伤与疗愈 · 交互学习页

《Attachment, Trauma, and Healing: Understanding and Treating Attachment Disorder in Children, Families and Adults》（第 2 版，2014）的**快速了解模式**学习页。用 [learn-from-materials](https://github.com/dmoshehun-prog/learn-from-materials) 技能生成。

## 打开

- 在线：启用 GitHub Pages 后访问仓库主页
- 本地：直接用浏览器打开 `index.html`（完全离线单文件，无任何外部请求）

## 内容

| 项目 | 数量 |
|---|---|
| 核心框架 | 22 |
| 内容单元 | 14（13 章 + 附录 A–I） |
| 术语 | 37（含英文全称与中文含义） |
| 行动规则 | 15（统一为「当 X，做 Y，因为 Z」） |
| 自检考点 | 45 |
| 框架间关系边 | 15 |
| 整体方法论 | 14 节点 / 14 边 |

页面固定提供六个模块：核心框架（卡片 + 框架关系图）、内容导学、术语大全、行动规则（卡片 + 整体方法论流程图）、学习自检、我的笔记。

## 出处可追溯

每项内容都带真实出处，格式为「第 N 章《章节标题》 · 原书第 X–Y 页 · PDF第 X–Y 页」。

- `knowledge-base/quick-audit.json` —— 覆盖全部 **482** 个来源块的结构账本，以及 **137** 条逐项出处核查（含原文短摘录）
- `knowledge-base/source_map.json` —— 页面级来源 ID 与内容 SHA-256
- `knowledge-base/coverage-audit.md` —— 覆盖范围说明

## 关于版权

**本仓库不包含原书正文。** 知识库中的 `full_text.txt` / `full_text.md`（原书完整正文，167,084 词）已刻意排除，请勿将其加入本仓库。

原书版权归 Terry M. Levy 与 Michael Orlans 所有（© 1998, 2014，Jessica Kingsley Publishers）。本页是基于该书的**学习笔记与摘要**，包含为标注出处而使用的少量短引用，不替代原书，也不构成对原书的转载。

## 关于内容性质

第 7–8 章描述的是作者自述的临床模型（Corrective Attachment Therapy / Corrective Attachment Parenting）。本页如实转述其方法、适用条件与作者自陈的局限，**不做独立疗效评价**——作者本人也未提供该模型的随机对照试验数据。

本页**不构成医疗建议**，也不提供可操作的临床指导。涉及儿童虐待、性侵与临床干预的描述保持原文范围。

## 交付校验状态

- 内容契约校验：通过
- 快速导读校验：通过（482 来源块全覆盖、137 条出处核查）
- 静态验证：通过
- 关系图门禁：通过（4 个框架节点在当前证据下无框架间连线，如实标注为 warning，未编造关系）
- 浏览器视觉验收：**未运行**（生成环境无 Playwright，按技能规范未擅自安装依赖）。交付清单为 `static-only`，`visualReview: not-run`。

## 生成信息

- `pageId`：`attachment-trauma-healing`（跨重新生成保持稳定，浏览器的笔记与错题以它为作用域）
- 学习深度：`quick`（核心导读，非全量知识整理）
- 输出语言：`zh-CN`

## 许可

本页笔记与摘要部分采用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 许可，使用时请注明原书与作者。
