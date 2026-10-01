# 发布日历与复盘

> 汇总上周发布数据 → 识别高完播选题方向 → 排本周日历

工作流 `wf-local-video-review`　·　归属 探店短视频编导　·　触发 定时（每周一）　·　
复杂度 M（需读取平台数据）　·　阶段 P1

## 调用链

- `本地热点监控`（local-trend-monitor）
- `平台格式适配`（platform-format-adapter）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 探店短视频编导 的「发布日历与复盘」：<你的输入>
```
