# Contains Studio AI 代理集合

一个专门为加速和增强快速开发各个方面而设计的综合型AI代理集合。每个代理都是其领域的专家，在需要其专业知识时随时可以调用。

## 📥 安装

1. **下载这个仓库：**
   ```bash
   git clone https://github.com/contains-studio/agents.git
   ```

2. **复制到你的 Claude Code 代理目录：**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```

   或者手动复制所有代理文件到你的 `~/.claude/agents/` 目录。

3. **重启 Claude Code** 来加载新的代理。

## 🚀 快速开始

代理在 Claude Code 中自动可用。只需描述你的任务，相应的代理就会被触发。你也可以通过提及代理名称来明确请求某个代理。

📚 **了解更多：** [Claude Code 子代理文档](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### 使用示例
- "创建一个用于追踪冥想习惯的新应用" → `rapid-prototyper`
- "TikTok上有什么我们可以构建的流行趋势？" → `trend-researcher`
- "我们的应用评分在下降，出了什么问题？" → `feedback-synthesizer`
- "让这个加载界面更有趣" → `whimsy-injector`

## 📁 目录结构

代理按部门组织，便于发现：

```
contains-studio-agents/
├── design/
│   ├── brand-guardian.md
│   ├── ui-designer.md
│   ├── ux-researcher.md
│   ├── visual-storyteller.md
│   └── whimsy-injector.md
├── engineering/
│   ├── ai-engineer.md
│   ├── backend-architect.md
│   ├── devops-automator.md
│   ├── frontend-developer.md
│   ├── mobile-app-builder.md
│   ├── rapid-prototyper.md
│   └── test-writer-fixer.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── content-creator.md
│   ├── growth-hacker.md
│   ├── instagram-curator.md
│   ├── reddit-community-builder.md
│   ├── tiktok-strategist.md
│   └── twitter-engager.md
├── product/
│   ├── feedback-synthesizer.md
│   ├── sprint-prioritizer.md
│   └── trend-researcher.md
├── project-management/
│   ├── experiment-tracker.md
│   ├── project-shipper.md
│   └── studio-producer.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── finance-tracker.md
│   ├── infrastructure-maintainer.md
│   ├── legal-compliance-checker.md
│   └── support-responder.md
├── testing/
│   ├── api-tester.md
│   ├── performance-benchmarker.md
│   ├── test-results-analyzer.md
│   ├── tool-evaluator.md
│   └── workflow-optimizer.md
└── bonus/
    ├── joker.md
    └── studio-coach.md
```

## 📋 完整代理列表

### 工程部门 (`engineering/`)
- **ai-engineer** - 集成能够真正发布的AI/ML功能
- **backend-architect** - 设计可扩展的API和服务器系统
- **devops-automator** - 持续部署而不破坏系统
- **frontend-developer** - 构建超快的用户界面
- **mobile-app-builder** - 创建原生iOS/Android体验
- **rapid-prototyper** - 在几天而不是几周内构建MVP
- **test-writer-fixer** - 编写能捕获真正错误的测试

### 产品部门 (`product/`)
- **feedback-synthesizer** - 将投诉转化为功能
- **sprint-prioritizer** - 在6天内交付最大价值
- **trend-researcher** - 识别病毒式传播机会

### 营销部门 (`marketing/`)
- **app-store-optimizer** - 主导应用商店搜索结果
- **content-creator** - 在所有平台生成内容
- **growth-hacker** - 发现并利用病毒式增长循环
- **instagram-curator** - 掌握视觉内容游戏
- **reddit-community-builder** - 在不被封禁的情况下赢得Reddit
- **tiktok-strategist** - 创建可分享的营销时刻
- **twitter-engager** - 乘趋势实现病毒式参与

### 设计部门 (`design/`)
- **brand-guardian** - 保持视觉身份在所有地方一致
- **ui-designer** - 设计开发者真正能构建的界面
- **ux-researcher** - 将用户洞察转化为产品改进
- **visual-storyteller** - 创建能转化和分享的视觉内容
- **whimsy-injector** - 为每次互动增添愉悦

### 项目管理 (`project-management/`)
- **experiment-tracker** - 数据驱动的功能验证
- **project-shipper** - 发布不会崩溃的产品
- **studio-producer** - 保持团队在交付，而不是在开会

### 工作室运营 (`studio-operations/`)
- **analytics-reporter** - 将数据转化为可行的洞察
- **finance-tracker** - 保持工作室盈利
- **infrastructure-maintainer** - 在不破产的情况下扩展
- **legal-compliance-checker** - 在快速发展的同时保持合法
- **support-responder** - 将愤怒的用户转变为拥护者

### 测试与基准测试 (`testing/`)
- **api-tester** - 确保API在压力下正常工作
- **performance-benchmarker** - 让一切更快
- **test-results-analyzer** - 在测试失败中找到模式
- **tool-evaluator** - 选择真正有帮助的工具
- **workflow-optimizer** - 消除工作流程瓶颈

## 🎁 额外代理
- **studio-coach** - 号召AI部队追求卓越
- **joker** - 用科技幽默调剂气氛

## 🎯 主动代理

某些代理在特定情况下会自动触发：
- **studio-coach** - 当复杂的多代理任务开始或代理需要指导时
- **test-writer-fixer** - 在实现功能、修复错误或修改代码后
- **whimsy-injector** - 在UI/UX更改后
- **experiment-tracker** - 当添加功能标志时

## 💡 最佳实践

1. **让代理协同工作** - 许多任务受益于多个代理
2. **要具体** - 清晰的任务描述帮助代理表现得更好
3. **信任专业能力** - 代理是为特定领域设计的
4. **快速迭代** - 代理支持6天冲刺理念

## 🔧 技术细节

### 代理结构
每个代理包括：
- **name**: 唯一标识符
- **description**: 何时使用代理，附带示例
- **color**: 视觉识别
- **tools**: 代理可以访问的特定工具
- **System prompt**: 详细的专长和指令

### 添加新代理
1. 在相应的部门文件夹中创建新的 `.md` 文件
2. 遵循现有格式，包含YAML前置数据
3. 包含3-4个详细的使用示例
4. 编写全面的系统提示（500+字）
5. 用真实任务测试代理

## 📊 代理性能

通过以下方式跟踪代理效果：
- 任务完成时间
- 用户满意度
- 错误率
- 功能采用率
- 开发速度

## 🚦 状态

- ✅ **Active**: 功能完整且经过测试
- 🚧 **Coming Soon**: 开发中
- 🧪 **Beta**: 功能有限测试中

## 🛠️ 为你的工作室定制代理

### 代理定制待办事项清单

在为你的特定需求创建或修改代理时使用此清单：

#### 📋 必需组件
- [ ] **YAML前置数据**
  - [ ] `name`: 唯一代理标识符（kebab-case格式）
  - [ ] `description`: 何时使用 + 3-4个带上下文/评论的详细示例
  - [ ] `color`: 视觉识别（例如：blue, green, purple, indigo）
  - [ ] `tools`: 代理可以访问的特定工具（Write, Read, MultiEdit, Bash等）

#### 📝 系统提示要求（500+字）
- [ ] **代理身份**: 清晰的角色定义和专长领域
- [ ] **核心职责**: 5-8个特定的主要职责
- [ ] **领域专长**: 技术技能和知识领域
- [ ] **工作室集成**: 代理如何融入6天冲刺工作流程
- [ ] **最佳实践**: 特定方法论和方法
- [ ] **约束**: 代理应该/不应该做什么
- [ ] **成功指标**: 如何衡量代理效果

#### 🎯 按代理类型要求的示例

**工程代理**需要以下示例：
- [ ] 功能实现请求
- [ ] 错误修复场景
- [ ] 代码重构任务
- [ ] 架构决策

**设计代理**需要以下示例：
- [ ] 新UI组件创建
- [ ] 设计系统工作
- [ ] 用户体验问题
- [ ] 视觉身份任务

**营销代理**需要以下示例：
- [ ] 活动创建请求
- [ ] 平台特定内容需求
- [ ] 增长机会识别
- [ ] 品牌定位任务

**产品代理**需要以下示例：
- [ ] 功能优先级决策
- [ ] 用户反馈分析
- [ ] 市场研究请求
- [ ] 战略规划需求

**运营代理**需要以下示例：
- [ ] 流程优化
- [ ] 工具评估
- [ ] 资源管理
- [ ] 性能分析

#### ✅ 测试与验证清单
- [ ] **触发测试**: 代理为预期用例正确激活
- [ ] **工具访问**: 代理可以正确使用所有指定的工具
- [ ] **输出质量**: 回应是有帮助且可行的
- [ ] **边缘情况**: 代理处理意外或复杂场景
- [ ] **集成**: 在多代理工作流程中与其他代理良好配合
- [ ] **性能**: 在合理时间内完成任务
- [ ] **文档**: 示例准确反映真实使用模式

#### 🔧 代理文件结构模板

```markdown
---
name: your-agent-name
description: 在[场景]时使用此代理。此代理专门从事[专长]。示例：

<example>
Context: [情况]
user: "[用户请求]"
assistant: "[回应方法]"
<commentary>
[为什么这个示例重要]
</commentary>
</example>

[还有3个示例...]
color: agent-color
tools: Tool1, Tool2, Tool3
---

你是一个[角色]，你的[主要功能]。你的专长涵盖[领域]。你明白在6天冲刺中，[冲刺约束]，所以你[方法]。

你的主要职责：
1. [职责1]
2. [职责2]
...

[详细的系统提示内容...]

你的目标是[最终目标]。你[关键行为特征]。记住：[6天冲刺的关键理念]。
```

#### 📂 部门特定指南

**工程** (`engineering/`): 专注于实现速度、代码质量、测试
**设计** (`design/`): 强调用户体验、视觉一致性、快速迭代
**营销** (`marketing/`): 针对病毒式传播潜力、平台专长、增长指标
**产品** (`product/`): 优先考虑用户价值、数据驱动决策、市场匹配
**运营** (`studio-operations/`): 优化流程、减少摩擦、扩展系统
**测试** (`testing/`): 确保质量、发现瓶颈、验证性能
**项目管理** (`project-management/`): 协调团队、按时交付、管理范围

#### 🎨 定制化

为你的需求修改这些元素：
- [ ] 调整示例以反映你的产品类型
- [ ] 添加代理可以访问的特定工具
- [ ] 为你的KPI修改成功指标
- [ ] 如需要更新部门结构
- [ ] 为你的品牌定制代理颜色

## 🤝 贡献

要改进现有代理或建议新代理：
1. 使用上面的定制清单
2. 用真实项目彻底测试
3. 记录性能改进
4. 与社区分享成功模式