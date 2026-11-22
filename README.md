<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/wordmark-dark.svg">
    <img src="assets/wordmark.svg" alt="AI4SCI" width="260">
  </picture>
</p>

**简体中文 · [English](README.en.md)**

# Special: 致敬基础势函数四周年 (2022.11.28-2026.11.28)

| Claude Fable 5.2 | GPT6 Astra | Gemini 4 Carbon |
| --- | --- | --- |
| https://github.com/user-attachments/assets/4610ac1d-d926-491c-8ffc-de0dc898e112 | https://github.com/user-attachments/assets/86a9e26b-ca36-411a-8f7b-0b2ac91dc5b8 | https://github.com/user-attachments/assets/6dc35325-f65d-46ca-ac2b-98ac35aeb865 |

<details>
<summary>查看视频制作提示词</summary>

清除记忆，新建一个项目。假设你是一个导演与 AI for Science 领域的资深人士。

用你最好的能力做一支 40 秒到 1 分钟的 MLFF foundational potential 四周年致敬动效视频（2022.11.28–2026.11.28），16:9 横版，无旁白，配原创音乐。

内容自己联网查证，讲这四年 MLFF foundational potential 的关键模型、里程碑、模型架构迭代（最好用示意图的形式展示，比如不变与等变，后续有的模型考虑了磁矩，如 CHGNet，以及电荷，如 [QET](https://arxiv.org/abs/2511.07249)），数据集的进步（比如多样性、数据规模、数据采集方法改进等，包括 OMat24、MatPES 等），对 AI for Science 领域的贡献（高通量筛选、加快分子动力学等）和相关研究数目的增长，不得杜撰。不要展示无意义或空洞的图片。

动手前先去 [Google](https://www.google.com/) 和 [Matbench Discovery](https://github.com/janosh/matbench-discovery) 等查找关于这些模型的详细资料。视觉结果要给人科技飞速进步的感觉。Matbench Discovery 如果出现，一定要在最后，因为它不是模型，而是对模型的总览与对比打分。

作为科研领域，相关的所有图片、表述等一定要严谨正确。节奏要快，动效密、画面饱满，消除 AI 感，随音乐卡点。

</details>

# AI4SCI · 科研计算与工业仿真情报

AI4SCI 面向材料、化学、医药、凝聚态物理及相关工业应用的研究者，汇集采用 AI 或科学计算的研究进展，并跟踪评测榜单、软件版本与企业研发动态。每条记录提供可回查的论文、评测或官方发布入口。

**[打开中文站][home] · [Open English site](https://ai4scihot.8-220-189-127.sslip.io/ai4scihot?lang=en) · [推荐信源][suggest]**

网站提供语言切换，同一栏目可以用中文或英文浏览。中文论文页提供摘要译文和推荐理由，可从原文入口核对研究方法与结论。英文论文页在可取得时展示作者原始英文摘要。部分开放获取论文附有全文导读。

## 浏览栏目

| 栏目 | 可以做什么 |
| --- | --- |
| [信息流][home] | 按原始发表日期浏览，结合领域、方法和关键词缩小范围。 |
| [科研周报][weekly] | 选择周次，补看该周精选研究。 |
| [学者与课题组][groups] | 按姓名、机构或研究方向查找团队并访问其主页。 |
| [机器学习力场][mlff] | 从 Matbench Discovery 总榜进入，按稳定性、结构优化、动力学、声子和热导等任务查看来源榜单，也可浏览 NIST CHIPS-FF 专项。 |
| [Agent4Science][agents] | 按实验设计、数据分析等科研环节浏览 Agent、工具和相关文献。 |
| [期刊会议追踪][journals] | 按出版方浏览期刊与会议论文集及其官方入口。 |
| [软件][software]与[仓库][repositories] | 在同一页切换两类目录，查看 VASP、LAMMPS、MOOSE、FAIRChem 等项目的跟踪重点、最近检查时间和官方更新。 |
| [企业追踪][industry] | 按公司或科研任务筛选材料、化学和药物研发动态，回查官方证据。 |
| [Skill 追踪][skills] | 查看 Academic Research Skills、Nature Skills 等科研技能项目及其正式版本。 |
| [收藏][bookmarks] | 找回此前保存的条目。收藏保存在当前浏览器。 |

## 从研究问题出发

- **找论文。** 例如关注药物递送中的分子模拟，可在信息流尝试「医药」和「仿真」筛选，先读摘要，再打开原文查证研究对象、方法和条件。
- **选力场。** 先选与工作最接近的评测任务，再沿来源链接核对数据集、指标和模型版本。
- **跟版本。** 在软件仓库追踪中找到项目，从官方发布说明判断数值修复、模型权重或接口变更是否影响现有工作。

## 推荐信源

先在[线上期刊会议目录][journals]、[软件与仓库目录][software]或[信源目录快照](SOURCES.md)查重，再[提交信源推荐][suggest]。提供官方链接、类别和持续跟踪的理由，例如哪个 Release 会说明模型权重与 ASE 接口的兼容性。有关选题和证据核对方式，可阅读[关于本站][about]。

[home]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot?lang=zh
[weekly]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/weekly?lang=zh
[groups]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/groups?lang=zh
[mlff]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/mlff?lang=zh
[agents]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/agent4science?lang=zh
[journals]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/sources?lang=zh
[software]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/software?lang=zh
[repositories]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/software?lang=zh#repositories
[industry]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/enterprise?lang=zh
[skills]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/skills?lang=zh
[bookmarks]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/starred?lang=zh
[about]: https://ai4scihot.8-220-189-127.sslip.io/ai4scihot/about?lang=zh
[suggest]: https://github.com/zz11ss11zz/AI4SCINEWS/issues/new?template=source.yml
