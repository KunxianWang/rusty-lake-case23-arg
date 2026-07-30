# Rusty Lake Case 23 ARG

《锈湖档案：23号案》是一款已经完成的非官方《Rusty Lake / Cube Escape》单页网页调查游戏。

玩家将进入一个由地方图书馆志愿者建立、早已停止维护的旧档案网站，从 1971 年劳拉·范德布姆死亡案开始，调查旧报纸、警察记录、病历、族谱、地产档案和损坏的网页备份，逐步还原锈湖的记忆、轮回与家族历史。

## 当前状态

- 完整游戏位于 `src/index.html`
- 六个调查阶段、31 份核心档案、4 份方块分类与 6 份隐藏档案均已接入
- 29 个主线关键词、9 个可选关键词和 P1—P8 八个谜题均可完整游玩
- 已完成自动存档、导入导出、四份固定证据、理论记录、三级提示和无障碍设置
- 已通过从空存档到 `CASE 24` 的黄金路径、提前猜词、错误反馈、XSS、损坏存档恢复和 HTML 结构检查
- 当前版本无需安装、构建、联网或服务器，可直接离线打开

## 直接游玩

用现代浏览器直接打开 [`src/index.html`](src/index.html)。

首页只公开三份初始材料。建议先阅读地方新闻剪报，从纸面边注获得第一个搜索词；如果希望立即开始，也可以在搜索框输入：

```text
CASE 23
```

游戏会自动保存到当前浏览器。需要换设备时，可在“设置”中导出和导入 JSON 存档。

需要完整剧透路线时，请查看：

- [完整游戏攻略](docs/game-walkthrough.md)

## 项目结构

```text
.
├── AGENTS.md
├── README.md
├── docs/
│   ├── complete-story.md
│   ├── rusty-lake-case23-outline.md
│   ├── search-keyword-flow.md
│   ├── full-game-flow.md
│   ├── game-walkthrough.md
│   ├── web-architecture-engineering.md
│   └── production-workflow.md
├── story/
│   ├── characters/
│   ├── chapters/
│   ├── continuity/
│   ├── plot/
│   └── story.md
├── src/
│   └── index.html    # 完整游戏：HTML、CSS、JavaScript 与内容数据全部内嵌
└── assets/           # 当前版本不依赖外部素材
```

## 完整内容基线

| 内容 | 数量 |
|---|---:|
| 核心档案 | 31 |
| 方块分类 | 4 |
| 隐藏档案 | 6 |
| 主线关键词 | 29 |
| 可选关键词 | 9 |
| 必要谜题 | 8 |
| 玩家理论阶段 | 7 |

最终报告不会要求玩家选择 Laura 的唯一凶手，而是检查六项关系结论、两份独立证据与正确证据等级。结案状态为 `NOT APPLICABLE TO LINEAR CAUSALITY`。

## 设计文档入口

- [完整剧情圣经](docs/complete-story.md)
- [玩法与页面大纲](docs/rusty-lake-case23-outline.md)
- [搜索关键词与具体流程](docs/search-keyword-flow.md)
- [完整游戏流程、输入输出与剧情脚本](docs/full-game-flow.md)
- [完整游戏攻略](docs/game-walkthrough.md)
- [网页架构与工程设计](docs/web-architecture-engineering.md)
- [完整制作流程与验收表](docs/production-workflow.md)
- [结构化故事工程](story/story.md)

## 设计原则

- 玩家是调查者，不会被强行写入锈湖正史。
- 从一宗普通死亡案开始，逐渐揭露记忆方块、轮回和锈湖管理者。
- 保留劳拉死亡原因的暧昧性，不创造原作未确认的唯一凶手。
- 明确区分“原作明确事实”“强烈暗示”和“同人补充”。
- 旧网站视觉不能牺牲可用性；所有必要谜题都需要公平线索和渐进提示。

## 免责声明

这是非商业、非官方的粉丝创作项目，与 Rusty Lake 官方团队无关。Rusty Lake、Cube Escape 及相关角色和世界观归其权利人所有。项目后续不应直接复制原作美术、音乐、商标或付费素材。
