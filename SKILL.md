---
slug: content-matrix-pay-7400cfba
displayName: 内容矩阵运营 Pro（AI 付）
name: content-matrix-pay
version: 1.0.0
summary: 小红书+抖音双平台内容矩阵运营——按次付费 ¥0.50/次
description: >
  面向品牌方、MCN机构、自媒体运营者的双平台内容矩阵运营系统（付费版）。
  通过支付宝 AI 按量付费，每次调用返回专业级运营方案。
  当用户提到"小红书运营""抖音运营""内容矩阵""多账号运营""爆款内容""短视频脚本"
  "内容排期""数据分析""竞品分析""MCN""品牌内容""种草笔记"时使用。
license: MIT
metadata:
  author: user_7400cfba
  tags:
    - social-media
    - content-marketing
    - xiaohongshu
    - douyin
    - paid-skill
---

# 内容矩阵运营 Pro（AI 付）

本 Skill 通过**支付宝 AI 按量付费**提供服务，单价 ¥0.50/次。

## 核心原则

1. **平台差异化**：小红书重图文种草，抖音重短视频
2. **数据驱动**：基于平台算法和真实数据
3. **矩阵协同**：多账号内容互补
4. **合规底线**：遵守平台规范

## 付费说明

服务地址: `https://am-server-content-matrix-ofbzuzmvbr.cn-hangzhou.fcapp.run/api/content-matrix`
服务单价: ¥0.50/次
ServiceID: API_D1FADD272D944284

### 支付流程
1. 调用 API → 收到 402 + Payment-Needed 头
2. 引导用户支付宝支付 ¥0.50
3. 携带 Payment-Proof 重试请求
4. 获取结果

## 能力路由

| 用户意图 | Action |
|---------|--------|
| 多账号布局 | `matrix-plan` |
| 爆款内容生成 | `content-generate` |
| 发布排期优化 | `schedule-optimize` |
| 数据复盘分析 | `data-analyze` |

## 免责声明
⚖️ 本工具仅供参考，不构成增长承诺。