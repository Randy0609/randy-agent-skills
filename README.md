# Randy Agent Skills

Randy 的公开 Agent Skills 总目录。

这个仓库负责分类、导航和核验来源，不复制各 Skill 的源码。每个 Skill 的原始仓库及其中的 `SKILL.md` 是唯一来源，避免同一 Skill 在多个仓库出现版本漂移。

最后核验：2026-08-14

## Skills

| 分类 | Skill | 用途 | 类型 | 唯一来源 |
|---|---|---|---|---|
| 审查与反证 | Adversarial Audit | 对方案、报告、研究结论或代码变更做只读对抗式审查 | 独立 Skill | [仓库](https://github.com/Randy0609/adversarial-audit) · [SKILL.md](https://github.com/Randy0609/adversarial-audit/blob/main/SKILL.md) |
| 问题重构 | First Principles | 从事实、真实约束和最小证伪测试重新推导方案 | 独立 Skill | [仓库](https://github.com/Randy0609/first-principles) · [SKILL.md](https://github.com/Randy0609/first-principles/blob/main/SKILL.md) |
| 事实质检 | Checking Facts for Ecommerce | 审计电商材料里的数字、证言、资质、承诺和因果归因 | 独立 Skill | [仓库](https://github.com/Randy0609/checking-facts-ecommerce) · [SKILL.md](https://github.com/Randy0609/checking-facts-ecommerce/blob/main/SKILL.md) |
| 目标工程 | Randy Goal Compiler | 把模糊需求编译成可执行、可验收且不扩权的 Goal Contract | 独立 Skill | [仓库](https://github.com/Randy0609/randy-goal-compiler) · [SKILL.md](https://github.com/Randy0609/randy-goal-compiler/blob/main/SKILL.md) |
| 电商内容工具 | OBS Studio | 规划和操作 AI 电商直播、录制、Browser Source 与 OBS 自动化 | 项目内嵌 Skill | [项目](https://github.com/Randy0609/ai-ecommerce-obs) · [SKILL.md](https://github.com/Randy0609/ai-ecommerce-obs/blob/main/obs-studio/SKILL.md) |

机器可读目录见 [`catalog.yaml`](catalog.yaml)。

## 使用原则

1. 先进入唯一来源仓库，阅读当前 README、`SKILL.md` 和依赖说明。
2. 按来源仓库提供的安装方式使用，不从本目录复制过期版本。
3. 兼容平台、运行依赖和验证结果以来源仓库当前内容为准。
4. 发现目录与来源不一致时，以来源仓库为准并更新本目录。

## 收录门槛

一个项目只有满足以下条件，才会作为 Skill 收录：

- 存在可读取的 `SKILL.md`；
- 能明确说明触发场景、边界和输出；
- 能定位到唯一来源仓库和文件路径；
- 不包含凭据、Cookie、Token、客户隐私或未公开经营数据。

## 公开与私有边界

本仓库只列出公开 Skill，不披露私有 Skill 的名称、用途或仓库路径。内部 Skill 使用独立的私有目录管理。

## License

本目录内容使用 [MIT License](LICENSE)。各 Skill 源码继续遵循其唯一来源仓库中的许可证。
