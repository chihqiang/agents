# agents

个人技术知识库与技能练习合集。

## 安装技能

使用 `npx skills add` 命令安装技能：

```bash
# 全局所有平台所有技能
npx skills add chihqiang/agents -g --all

# 安装指定平台所有技能
npx skills add chihqiang/agents --skill '*' -a opencode

# 安装指定技能（--skill 参数使用技能目录名 {skill-name}）
npx skills add chihqiang/agents --skill async-python-patterns
```

> **参数说明**：`--skill` 参数应使用技能的**目录名**（即 `{skill-name}`），对应 `agents/python-development/{skill-name}/` 目录。

## 技能目录

### Python Development

| skill-name | 描述 |
|------------|------|
| [async-python-patterns](./plugins/python-development/skills/async-python-patterns/SKILL.md) | Python asyncio、并发编程和 async/await 模式 |
| [python-background-jobs](./plugins/python-development/skills/python-background-jobs/SKILL.md) | 任务队列、工作者和事件驱动架构 |
| [python-code-style](./plugins/python-development/skills/python-code-style/SKILL.md) | 代码规范，包括命名约定、文档字符串、代码格式 |
| [python-configuration](./plugins/python-development/skills/python-configuration/SKILL.md) | 项目配置管理，包括环境变量、配置文件处理 |
| [python-design-patterns](./plugins/python-development/skills/python-design-patterns/SKILL.md) | 设计模式，包括 KISS、单一职责、组合优于继承 |
| [python-error-handling](./plugins/python-development/skills/python-error-handling/SKILL.md) | 错误处理模式，包括输入验证、异常层次结构 |
| [python-performance-optimization](./plugins/python-development/skills/python-performance-optimization/SKILL.md) | 性能优化技巧和最佳实践 |
| [python-resilience](./plugins/python-development/skills/python-resilience/SKILL.md) | 弹性模式，包括自动重试、指数退避、超时和容错装饰器 |
| [python-resource-management](./plugins/python-development/skills/python-resource-management/SKILL.md) | 资源管理和上下文管理器使用 |
| [python-sqlalchemy](./plugins/python-development/skills/python-sqlalchemy/SKILL.md) | Python ORM 和 SQL 工具包，支持异步操作 |
| [python-testing-patterns](./plugins/python-development/skills/python-testing-patterns/SKILL.md) | 测试策略，包括 pytest、fixtures、mock 和 TDD |
| [python-type-safety](./plugins/python-development/skills/python-type-safety/SKILL.md) | 类型安全，包括类型注解、类型检查工具 |

### Shell Scripting

| skill-name | 描述 |
|------------|------|
| [bash-defensive-patterns](./plugins/shell-scripting/skills/bash-defensive-patterns/SKILL.md) | Bash 防御性编程技术，用于生产级脚本 |
| [shellcheck-configuration](./plugins/shell-scripting/skills/shellcheck-configuration/SKILL.md) | ShellCheck 静态分析配置和使用 |
| [bats-testing-patterns](./plugins/shell-scripting/skills/bats-testing-patterns/SKILL.md) | Bats（Bash Automated Testing System）测试模式 |

### Frontend Development

| skill-name | 描述 |
|------------|------|
| [react-state-management](./plugins/frontend-development/skills/react-state-management/SKILL.md) | React 状态管理，包括 Redux Toolkit、Zustand、Jotai |
| [tailwind-design-system](./plugins/frontend-development/skills/tailwind-design-system/SKILL.md) | Tailwind CSS v4 设计系统和组件库构建 |
| [vue](./plugins/frontend-development/skills/vue/SKILL.md) | Vue 3 Composition API、script setup、响应式系统 |
| [vue-best-practices](./plugins/frontend-development/skills/vue-best-practices/SKILL.md) | Vue.js 最佳实践工作流 |
| [vue-router-best-practices](./plugins/frontend-development/skills/vue-router-best-practices/SKILL.md) | Vue Router 4 模式和导航守卫 |
| [vue-testing-best-practices](./plugins/frontend-development/skills/vue-testing-best-practices/SKILL.md) | Vue.js 测试最佳实践 |
| [pinia](./plugins/frontend-development/skills/pinia/SKILL.md) | Pinia Vue 状态管理库 |
| [pnpm](./plugins/frontend-development/skills/pnpm/SKILL.md) | Node.js 包管理器 |
| [tsdown](./plugins/frontend-development/skills/tsdown/SKILL.md) | TypeScript/JavaScript 库打包工具 |
| [tauri](./plugins/frontend-development/skills/tauri/SKILL.md) | Tauri 框架，用于构建跨平台应用 |
| [tailwindcss](./plugins/frontend-development/skills/tailwindcss/SKILL.md) | Tailwind CSS v4 框架，用于快速构建响应式 UI |

### Rust Development

| skill-name | 描述 |
|------------|------|
| [rust](./plugins/rust-development/skills/rust/SKILL.md) | Rust 最佳实践工作流 |

## 使用方式

1. **浏览技能文档**：直接查看对应技能的 `SKILL.md` 文件
2. **学习参考**：每个技能文档包含详细的使用说明和代码示例
3. **贡献技能**：按照现有格式添加新的技能模块

## 感谢

- [wshobson/agents](https://github.com/wshobson/agents)
- [vercel-labs/skills](https://github.com/vercel-labs/skills)
- [rolldown/tsdown](https://github.com/rolldown/tsdown)
- [vuejs-ai/skills](https://github.com/vuejs-ai/skills)
- [martinholovsky/claude-skills-generator](https://github.com/martinholovsky/claude-skills-generator)

## 许可证

本项目采用 [Apache-2.0](LICENSE) 许可证。
