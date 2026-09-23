# SOL 3H Post-L0 Trajectory Review Materials (V0.1)

本仓库是 **SOLUSDT 现货 3H** 的「L0 后连续轨迹」观察研究材料，用于外部审阅与候选轨迹状态语言设计。

## 说明

- 研究对象：SOLUSDT Spot，3H 周期，L0 后连续轨迹观察。
- 数据来源：Binance Spot 已收盘 K 线（3H）。
- 内容仅用于**现象研究**与**状态语言设计**，**不包含任何买卖建议**。
- 本仓库**未包含完整 Master 数据集**，也**不包含任何账户信息**。
- 图表位于 `charts/` 目录（每案例一张自包含 HTML，内联 SVG，可离线打开）。

## 研究状态

`POST_L0_TRAJECTORY_DATA_PREP_PASS`

## 目录

| 文件 | 内容 |
| --- | --- |
| `selected_cases.csv` | 选取的代表案例及选取原因 |
| `case_summary.json` | 逐案例客观事实画像与全局计数 |
| `field_dictionary.json` | 逐字段说明与五维映射对照 |
| `CURRENT_CASE_20260916_2100.json` | 当前重点案例逐根完整输出 |
| `candidate_legs.csv` | 候选进攻/回调/恢复腿段材料（多个并列版本） |
| `POST_L0_TRAJECTORY_V01_REPORT.md` | 研究主报告 |
| `charts/` | 24 张逐案例诊断图 |
| `SHA256SUMS.txt` | 发布文件的相对路径、字节数与 SHA256 |

## 边界声明

- 未运行统计检验、回测、参数优化或信号扫描。
- 未创建最终状态公式；候选腿段仅为材料，不构成最终标签。
- 未修改任何上游冻结产物。
