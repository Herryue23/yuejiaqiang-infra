# MEMORY.md · 核心状态快照 · 2026-06-22更新版

## ⚠️ 永久规则索引（本文件不写完整规则，只索引）
- P0红线/证据等级/危险词/STOP-RUN-VERIFY → SOUL.md
- 搜索流程/工具使用/扣子踩坑 → TOOLS.md
- 岳岳偏好/沟通风格/授权边界 → USER.md
- 每轮运行检查清单 → HEARTBEAT.md
- 敏感凭证 → SECRET.md（不进版本控制）

## 🔴 事故复盘索引（永久警示）
**05-29撒谎事件（永久记录，根因：局部完成≠全局完成）：**
1. "谁都能看"：未检查前端登录页就下结论
2. "真实采购数据"：把后端API通了误当成前端可见

→ 完整复盘见 SOUL.md 红线一 / 危险词触发器

## 🔴 核心认知（永久原则）
- prompt靠不住，只有确定性逻辑靠得住
- 扣子唯一可靠的是 Workflow（软约束→硬拦截）
- 数据源层级：T1权威→T2行业报告→T3电商→T4媒体→T5社交→T6论坛

## 🔐 授权与凭证（已确认安全）
- 专家辅助对话：xsimplechat.com/chat，账号herryue（密码在SECRET.md）
- 基建备份仓库：github.com/Herryue23/yuejiaqiang-infra

## 🔒 永久确认规则（无用户指令不得变更）
1. WEEE注册处于等待状态，无用户特殊指令不得主动变更
2. DOOH官网存档已定稿，无用户明确允许禁止擅自修改
3. 调用create_project时，禁止将子项目名传入主Bot名称字段

## 📂 活跃项目状态

### 🔴 星图AI教培
- 状态：pm_super_chatflow9节点全量测通
- 下一步：关停5个旧技能即可上线
- 全链路耗时：1分23秒

### 🔴 Heaven's Clock V1.1
- 状态：定版待岳岳验收

### 🟡 DOOH德国LED
- 状态：视频Agent全套SOUL/TOOLS+2份知识库过闸机4关交付
- 阻塞（26天）：Google域名验证 / WEEE注册号 / WhatsApp Business号
- 禁止：擅自修改官网存档

### 🟢 海外DTC / 巢趣
- 状态：暂缓

## 🔧 技术记录（GPT诊断优化：删除工具流程，保留非重复项）
- 抖音提取命令：agent-browser open → wait --load networkidle → get text body
- 扣子2026年6月30日后新建OpenClaw项目路径：新建Agent → 创建云端Agent → 选择OpenClaw框架
- 终止方向：接入外部Claude Code/OpenClaw搭建跨平台协作系统不可行
- 外部模型（GPT/Claude/Gemini/DeepSeek）→ XSimple专家通道
