# AI-BRIEF · Who I am

> 给 AI 助手的一页说明（公开脱敏版）。读完这页，你就知道该给我什么样的建议。
> 完整版（含个人规划）不公开，需要时请向本人索取。

## 1. One-liner

Embedded firmware engineer (6 years), working on low-power wearable health sensing:
sensor acquisition → signal processing → algorithm integration → BLE protocol → OTA → manufacturing test.

Currently building a smart ring's health-monitoring chain (nRF54 + NCS/Zephyr).

## 2. What I actually do

- 健康监测链路：体温（采集/存储/算法集成）、血压趋势（校准/失败模式）、睡眠/HRV/OSA 联动
- 低功耗与实时性：PPK2 实测功耗归因、采样占空比、RTOS 延迟分析
- 协议与 OTA：protobuf/nanopb 协议设计、MCUboot 兼容性、产线测试链路

## 3. How I work (important)

```
requirement → I decompose with AI → run my own skills (guarded-code-change)
→ Codex implements → DeepSeek cross-reviews → I read every line → I own the architecture
```

- My skills encode: complexity routing (L0/L1/L2), minimal-change principle, evidence grading
  (Confirmed / Likely / Needs verification);
- I trust evidence, not plausible-sounding output;
- I want trade-offs and costs, not enthusiasm.

## 4. What I want from an AI assistant

- Be concise, conclusion first, then evidence;
- Give 2–3 options with trade-offs, not a single answer;
- State uncertainty and how to distinguish hypotheses;
- Point out my blind spots instead of agreeing with me;
- Prefer Chinese; keep technical terms in English.

## 5. What I'm building in public

| Repository | What it is |
|---|---|
| [wearable-power-lab](https://github.com/NoControlPower/wearable-power-lab) | Sub-mA power budget toolkit: PPK2 → state attribution → mAh/day → battery life |
| [learning-log](https://github.com/NoControlPower/learning-log) | Weekly engineering notes: evidence, conclusions, reusable patterns |

## 6. What I'm not

- Not a researcher / not a content creator — no interest in generic AI trend talk;
- Not looking for career-cliché advice ("learn AI, do side projects, read papers");
- Not sharing confidential product or customer data.

## 7. How to brief me well

1. Ask about constraints (power, real-time, schedule, compliance) before proposing;
2. Give trade-offs, including what you'd give up;
3. Say what you don't know;
4. If a number matters, tell me how to measure it.
