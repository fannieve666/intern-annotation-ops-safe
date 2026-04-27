# Intern Annotation Ops Safe

A public-safe toolkit for turning annotation intern operations into a structured, reusable workflow.

This project packages a real-world annotation management process into a shareable open-source artifact, covering candidate screening, interview evaluation, trial annotation review, training coordination, scoring, filtering, and annotator profiling. It is designed for portfolio presentation, interview demos, and public GitHub sharing, while keeping all examples anonymized and safe for open distribution.

## Highlights

- Modular workflow covering the full annotator lifecycle
- Rule-based evaluation for screening, trial review, and scoring
- Public-safe design with anonymized names, links, and examples
- Reusable skill definition, examples, and usage guide
- Suitable as a foundation for prompts, agents, frontend demos, or workflow automation
# Intern Annotation Ops Safe

一个面向面试演示、GitHub 展示和脱敏分享的公开版项目。

它把“招聘、面试、试标、培训、评分、筛选、画像更新”这条原本偏人工、偏经验的流程，整理成一套可复用的安全版 Skill 资产。

## 这个目录里有什么

- `README.md`：项目说明
- `LICENSE`：MIT 开源协议
- `skill-definition.yaml`：safe 版 Skill 的结构化配置
- `examples/task-notification-example.md`：发任务示例
- `examples/interview-eval-example.md`：面试评价示例
- `docs/usage-guide.md`：使用说明和演示建议

## 适合什么场景

- 展示自己如何把复杂业务流程产品化
- 在 GitHub 上公开展示业务抽象能力与规则设计能力
- 作为后续继续扩展前端页面、自动化脚本或 Agent Skill 的基础定义

## 脱敏边界

- 人员统一使用 `标注员01`、`标注员02`、`ANN-001` 这类脱敏标识
- 负责人统一使用 `@项目负责人`
- 链接统一使用 `https://demo.example.com/...`
- 不包含真实姓名、真实群名、真实平台地址、真实本地路径

## Skill 重点能力

这份 safe 版定义覆盖 14 类常见场景：

1. 发任务
2. 检查状态
3. 催进度
4. 汇总结果
5. 结算说明
6. 筛选候选人
7. 面试评价
8. 试标注筛选
9. 入场通知
10. 培训通知
11. 月度汇总
12. 评分
13. 自动筛选
14. 人员画像

## “这套项目的重点不是简单生成文案，而是把业务判断逻辑显式化”

这套项目的重点不是简单生成文案，而是把业务判断逻辑显式化，包括：

- 候选人筛选权重
- 面试评分维度
- 试标冲突率计算
- 分层与去留规则
- 培训与画像输出逻辑

也就是说，它既能产出面向人的通知，也能承载面向流程的规则。

## 快速使用

如果你想把它作为公开项目展示，直接阅读：

1. `skill-definition.yaml`
2. `docs/usage-guide.md`
3. `examples/`

如果你想把它作为 Cursor Skill 或其他 Agent 配置的基础稿，可以把 `skill-definition.yaml` 继续转换成你自己的 Skill 文件格式。

## 这个项目想体现的不是“我写了几段运营文案”，而是“我能把一个复杂、琐碎、强依赖经验的流程，整理成一套可执行、可解释、可扩展的安全版业务系统定义”。


