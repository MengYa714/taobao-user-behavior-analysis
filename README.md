\# 淘宝用户行为数据分析 🛒



基于淘宝用户行为公开数据集，对百万级用户行为记录进行数据清洗与分析。旨在通过漏斗分析、同期群分析和帕累托分析挖掘用户行为特征，并提供综合运营建议。



![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge\&logo=matplotlib\&logoColor=white)

![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge\&logo=seaborn\&logoColor=white)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)



\## 📊 可视化看板

> 点击下方链接体验 Power BI 交互式看板（若已发布）：

> [🔗 点击查看交互式看板 Live Demo](你的PowerBI公开链接)



<!-- 如果没有发布链接，请把上面两行删掉，保留下面的截图 -->

![Dashboard](dashboard\_preview.png)



\## 📌 核心结论

\- \*\*超半数用户首月后流失\*\*，召回机制待加强。

\- \*\*品类高度集中\*\*，前20%品类贡献71%销量。

\- \*\*资源应集中投入头部品类\*\*。



\## 💡 综合运营建议

\- \*\*转化提升\*\*：针对加购未购买用户实施精准营销（限时优惠+库存提醒）。

\- \*\*留存提升\*\*：建立用户召回体系，在首购后7天黄金窗口内触达。

\- \*\*品类优化\*\*：资源向头部品类倾斜，长尾品类做清仓或淘汰。



\## 📂 项目产出文件

| 文件名 | 说明 |

| :--- | :--- |

| `funnel.png` | 漏斗分析可视化 |

| `cohort\_retention.png` | 同期群留存热力图 |

| `pareto\_category.png` | 品类帕累托分析图 |

| `pareto.png` | 帕累托分析图 |

| `淘宝用户行为数据分析报告.pdf` | 完整分析报告 |



\## 🛠️ 技术栈与方法论

\- \*\*技术栈\*\*：Python (Pandas, Matplotlib, Seaborn) — 数据清洗与分析；Power BI — 交互式可视化看板。

\- \*\*方法论\*\*：漏斗分析、同期群分析、帕累托分析。



\## ⚠️ 分析局限性

\- 数据采样50万行，可能存在采样偏差（高活跃用户占比偏高）。

\- 时间跨度约3个月，同期群分析仅覆盖2个完整群组。

\- 行为数据缺少用户人口统计信息和商品属性信息。

