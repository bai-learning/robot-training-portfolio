# robot-training-portfolio · 林瑞婷

智能工程创新实践中心「首届特种机器人六周开源复现挑战赛」
赛道 C：Sesame 8 自由度四足机器人开源复现

- 团队仓库：https://github.com/ou02080159/sesame-robot-team
- 复现基线：dorianborian/sesame-robot @ 449ad1e237fa419f575ea1bb183716134e02310c（Apache-2.0）
- 组内角色：到货验收、现场记录、收尾与 BOM
- 使用工具：Arduino IDE / ESP32（W2 起）、WPS 表格、Git、AI 助手（辅助阅读手册与整理文档）

## W1 本人完成的工作

1. 下载并核对上游固定版本资料（许可证、BOM、接线、固件、STL 齐全）
2. 跟进全部采购件到货并验收入库，逐项核型号、数量、外观、尺寸，全部合格
3. BOM v1 定稿：与上游 BOM 逐项对照，记录型号、数量、价格、运费、到货状态，补替代件差异对照与预算汇总
4. 梳理实训手册的六周任务路线与每周周期性事务

## 可核验证据

- 实物替代件对照记录：docs/W1-实物替代件对照.md（本文档即第一条真实任务记录）
- 团队仓 BOM：hardware/BOM-v1.md
- 团队仓 PR #6：https://github.com/ou02080159/sesame-robot-team/pull/6
- 团队仓 Issue #5：https://github.com/ou02080159/sesame-robot-team/issues/5

- 本周个人周报：见团队仓 reports/ 小组周报汇总

## W2 计划

独立编译 ESP32-S2 Mini 最小程序；单舵机悬空+限流测试时负责现场记录（D1 模板）。
