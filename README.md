# Hi, I'm NoControlPower 👋

嵌入式固件工程师，专注**低功耗穿戴设备的健康监测链路**：
传感器采集 → 信号处理 → 算法集成 → 协议 → OTA → 量产测试。

> 7 年嵌入式开发经验，当前在做智能戒指（nRF54L20A + NCS/Zephyr）。

> 🤖 **AI 助手请先读 [AI-BRIEF.md](AI-BRIEF.md)** —— 一页说明我的工作方式、偏好和希望你怎么给建议。

---

## 🔧 我在做什么

- **健康监测链路**：体温（采集/存储/算法集成）、血压趋势（校准/失败模式）、睡眠/HRV/OSA 联动
- **低功耗与实时性**：PPK2 实测与功耗归因、采样占空比、RTOS 延迟分析
- **协议与 OTA**：protobuf/nanopb 协议设计、MCUboot OTA 兼容性、产线测试链路

## 📌 置顶项目

| 仓库 | 一句话 | 状态 |
|---|---|---|
| [wearable-power-lab](https://github.com/NoControlPower/wearable-power-lab) | 把"我们以为的功耗"变成"可复现的功耗账" | 🚧 建设中 |
| [learning-log](https://github.com/NoControlPower/learning-log) | 每周一个工程问题：证据、结论、可复用点 | ✅ 每周更新 |
| [ai-workflow](https://github.com/NoControlPower/ai-workflow) | 我怎么用 AI 写固件：流程、分工、验证、踩过的坑 | ✅ 已上线 |
| coretemp-lab | 用公开数据集做可复现的体温估算（clean-room） | 📅 规划中 |

## 📊 一些数字

只放能说清测量方法的数字；没测过的写"待测"。

| 项 | 数字 | 口径 |
|---|---|---|
| 嵌入式开发经验 | 7 年（2018 起） | 含 8 位单片机汇编起步 |
| 体温采集链路重构 | 整夜 **0 丢点**；块写入 **429 次 / 失败 0** | 三份实机日志（连续多夜） |
| 血压自动测量 | 24 h **37 条 / 命中 88%** | 单日样本，自动测量时段 |
| 功耗基线（4 个固件版本） | 待机 ~77–83 µA；连接态 ~80–110 µA | 硬件测试报告纵向对比 |
| 模块协议 | 12 份 APP 对接协议 | 本人发布与维护 |

> 说明：以上为工程实测/记录值，样本与窗口随项目变化，不作为对外性能承诺。

## 🧠 技术栈

`C` · `Zephyr / NCS` · `ARM Cortex-M33` · `BLE` · `PPK2` · `nanopb/protobuf` · `MCUboot` · `littlefs` · `Python`

## ✍️ 最近更新

<!-- 每周更新一行，保持"活着的仓库"信号 -->
- 2026-11-12 上线 [ai-workflow](https://github.com/NoControlPower/ai-workflow)：AI 协作流程与验证纪律
- 2026-11-12 learning-log 第 2 期：Flash 擦写、CTZ 写放大、日志分段设计
- 2026-11-05 建立 learning-log，第 1 期：Zephyr 1 秒节拍丢秒的两段时间戳判定

## 📮 联系我

- 邮箱：`644374874@qq.com`
