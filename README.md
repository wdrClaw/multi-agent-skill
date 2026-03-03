# Enterprise Dev Multi-Agent Skill Pack v1.2

这是一个面向企业研发流程的多 Agent 协作技能包，适用于：

- 旧项目迭代改造
- 新项目建设
- Web 全栈 + 独立服务端工程并存的组织结构

## 角色清单

1. 总控调度 Agent
2. 产品经理 Agent
3. 架构师 Agent
4. UI 设计 Agent
5. 服务端工程师 Agent
6. Web 全栈研发 Agent
7. 测试 Agent
8. DevOps Agent

## 核心原则

- 角色固定，技术栈不固定
- 先识别现状，再进行设计或实现
- 旧项目优先兼容、低侵入、可回滚
- 新项目优先架构清晰、契约明确、边界清楚
- 严格职责边界，禁止越权

## 主要文件

- `enterprise-dev-multi-agent-skill-pack-v1.2.yaml`：主配置文件
- `docs/agent-roles.md`：角色说明与职责边界摘要

## 使用建议

1. 先用真实旧项目样例验证“先识别后执行”是否稳定。
2. 再逐步补充你们公司的代码规范词典、目录规则、禁改区清单。
3. 如果平台不支持复杂字段，可先保留每个角色的 `system_prompt + input_contract + output_contract`。
