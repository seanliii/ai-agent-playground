# AI Agent Playground 🤖

> 一个可视化的 AI Agent 任务分解器，灵感来自 [agent-service-toolkit](https://github.com/JoshuaC215/agent-service-toolkit) (1.1k ⭐)

## 功能

- 输入复杂任务，AI Agent 自动分解为子步骤
- 可视化展示每个步骤的执行过程
- 支持真实 LLM API 调用（AISA / OpenAI 兼容）
- 演示模式（无需 API Key）

## 快速开始

1. 打开 `index.html`
2. 输入任务（或使用快捷任务）
3. 填入 API Key（可选）
4. 点击「分解任务」

## 技术栈

- 纯 HTML / CSS / JavaScript
- 调用 AISA API (OpenAI 兼容格式)
- 部署于 GitHub Pages

## 部署

```bash
bash /root/.openclaw/workspace/scripts/deploy_project_to_github.sh \
  projects/ai-agent-playground \
  ai-agent-playground
```

## 在线体验

https://seanliii.github.io/ai-agent-playground/

---

🦐 小蓝虾复刻版
