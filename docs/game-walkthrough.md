# 《锈湖档案：23号案》完整攻略

> 本文包含从开场到隐藏结局的完整剧透。想自行调查的玩家，请先直接打开 [`../src/index.html`](../src/index.html)。

## 开始前

- 游戏会自动保存进度；“设置”页可以导出或导入 JSON 存档。
- 搜索不区分大小写和常见标点，中文别名也可使用。本文统一列出标准关键词。
- 每次搜索后要打开结果档案并阅读；只搜索、不打开档案，部分谜题不会开放。
- 提前猜中后期关键词只会看到“目录存在”的索引说明，不能跳过前置调查。
- 谜题答错不会清空已填内容，也不会损失进度。每个谜题都有三级“项目组整理建议”。

## 极速主线路线

按以下顺序检索；遇到谜题时使用后文对应答案：

```text
CASE 23
Laura Vanderboom
Robert Hill
Dale Vandermeer
RL-23
RL-23 1971

RL-23 1972
M-138.4
CW-6
A. Vanderboom
RLM-X4
White Door
Robert Hill 1972
BLACK STATE

A. Vanderboom 1859
William Vanderboom
Elixir Life Death
VDB-TREE
Samsara 1935

RLH-1893
Dale Vandermeer 1939
D. Eilander
Paradise 1796
Harvey 1893

CAVE-4
WHITE BLACK BLUE
23-BLACK
CASE 23 STATUS
CASE 24
```

## 第一阶段：23号案

### P1：搜索教学

在首页阅读地方新闻剪报，找到案件编号，然后搜索：

```text
CASE 23
```

P1 会自动完成。打开搜索结果里的案件摘要与公开附件，再依次搜索并打开所有结果：

1. `Laura Vanderboom`
2. `Robert Hill`
3. `Dale Vandermeer`
4. `RL-23`
5. `RL-23 1971`

打开 `D08 三版现场照片` 后，可以切换并查看三个备份版本；这是隐藏结局条件之一。

### P2：现场保管链审计

提交前需要读过 `D04`、`D05`、`D06` 和 `D08`。正确顺序是：

1. 接警（18:20）
2. Dale 抵达（18:36）
3. 现场封闭（18:44）
4. 确认遗体消失（19:18）

审计结论：现场封闭后，没有任何普通的遗体运输或交接记录。完成后生成 `D10`，并开放 1972 年记录。

## 第二阶段：北岸磨坊与白门

搜索并打开：

1. `RL-23 1972`
2. `M-138.4`
3. `CW-6`
4. `A. Vanderboom`

### P3：磨坊同址关联

需要先读过 `D11`—`D14`。恰好选择以下三份材料：

- `D11` 电视静帧
- `D12` North Mill 138 房产卡
- `D13` M-138.4 电力故障单

三者共同证明图像、地产号与供电区域属于同一地点。完成后搜索：

```text
RLM-X4
```

### P4：RLM-X4 操作流程

正确顺序：

1. 对象在同步画面中出现
2. 将对象接入机器
3. 分离稳定与腐化记忆
4. 把结果储存为方块

随后完成白门调查：

1. `White Door`
2. `Robert Hill 1972`
3. `BLACK STATE`

`BLACK STATE` 此时只恢复 `23-BLACK` 的索引标题，这是正常状态。完成磨坊与白门两条线后，搜索：

```text
A. Vanderboom 1859
```

## 第三阶段：Vanderboom 家族

依次搜索并打开：

1. `William Vanderboom`
2. `Elixir Life Death`
3. `VDB-TREE`

### P5：VDB-TREE 族谱重建

| 字段 | 正确答案 |
|---|---|
| William 的兄弟 | Aldous |
| 继承 William 财产的人 | James |
| Emma 的孩子 | Frank |
| Samuel 与 Ida 的孩子 | Leonard |
| Rose 的父亲 | Albert |
| Rose 的下一代（1935） | Laura |
| William 的 revival root | Laura |

最后一项是复生仪式关系，不是普通父女关系。完成后搜索：

```text
Samsara 1935
```

### P6：灵药结果编目

| 人物 | 状态 | 后续身份或解释 |
|---|---|---|
| William | 死亡／等待重生 | 转生为 Laura |
| Aldous | 存活／永生 | 成为 Mr Crow |
| Laura | 1935 年出生 | William 转世且有独立人生 |

完成后开放 1893 年旅馆档案。

## 第四阶段：旅馆、Eilander 家族与 Dale

依次搜索并打开全部结果：

1. `RLH-1893`
2. `Dale Vandermeer 1939`
3. `D. Eilander`
4. `Paradise 1796`
5. `Harvey 1893`

### P7：面具与人物关系审计

| 旅馆形象 | Paradise 人物 |
|---|---|
| Mr Deer | Nicholas |
| Mr Boar | Gerard |
| Ms Pheasant | Elizabeth |
| Mr Rabbit | David |
| Mrs Pigeon | Margaret |

证据等级选择：

```text
高度相关／强暗示
```

不要选择“确认同一身份”：档案足以建立强关联，但没有普通身份记录层面的绝对确认。完成后开放 `CAVE-4`。

## 第五阶段：方块与冲突版本

搜索并打开洞穴设备图：

```text
CAVE-4
```

然后搜索：

```text
WHITE BLACK BLUE
```

必须依次打开四份方块分类：

- `F01 WHITE`
- `F02 BLACK`
- `F03 BLUE`
- `F04 GOLDEN / UNCONFIRMED`

四份都读过后搜索：

```text
23-BLACK
```

在 `D29` 中查看全部五种冲突版本：

1. 警署版本
2. Bob／White Door 版本
3. Black State 版本
4. Dale／Paradox 版本
5. North Mill 版本

全部查看后搜索：

```text
CASE 23 STATUS
```

## P8：最终关系报告

每题都要选择关系结论、证据等级和两份不同档案。下表给出一组可通过的答案；同一题也可能接受表中未列出的其他直接证据。

| # | 关系结论 | 等级 | 证据 A | 证据 B |
|---:|---|---|---|---|
| 1 | William Vanderboom | 原作明确 | D19 | D22 |
| 2 | Aldous Vanderboom | 原作明确 | D19 | D20 |
| 3 | Jakob 与 Caroline 的牺牲链 | 原作明确 | D23 | D26 |
| 4 | David Eilander—Mr Rabbit—1939 兔面链 | 高度相关／强暗示 | D24 | D25 |
| 5 | 提取并储存白／黑记忆 | 原作明确 | D13 | D15 |
| 6 | 被观察、测试，可能是继任候选 | 高度相关／强暗示 | D23 | D28 |

提交后，案件状态变为：

```text
CASE STATUS: NOT APPLICABLE TO LINEAR CAUSALITY
不适用线性因果
```

最后搜索：

```text
CASE 24
```

即可看到 `Dale Vandermeer — Status Pending` 尾声。

## 九个可选搜索

可选检索不会阻止主线通关，其中三项与隐藏结局有关。

| 编号 | 搜索词 | 用途 |
|---|---|---|
| O01 | `HARVEY` | 补充 Harvey 的跨年代目击记录 |
| O02 | `BLACK MOTHS` | 补充黑蛾与腐化记忆记录 |
| O03 | `CW-6 18:20` | 补充时钟与停电时间校验 |
| O04 | `D. MOOR CHECKSUM` | 查看扫描校验值与版本差异 |
| O05 | `D. EILANDER RABBIT` | 建立兔面秘密，隐藏结局条件 |
| O06 | `LAURA WILLIAM` | 补充 Laura 与 William 的转生索引 |
| O07 | `OWL CROW` | 补充 Mr Owl 与 Mr Crow 的交叉记录 |
| O08 | `GOLDEN CUBE` | 建立第四方块秘密，隐藏结局条件 |
| O09 | `ELEVATOR` | 进入隐藏湖面尾声 |

## 隐藏结局

先完成以下三个秘密：

1. 打开 `D08` 并查看全部三个现场照片版本。
2. 搜索 `D. EILANDER RABBIT` 并打开结果。
3. 搜索 `GOLDEN CUBE` 并打开结果。

完成 P8 最终报告后，再搜索：

```text
ELEVATOR
```

即可进入无文字的湖面、电梯与旅馆灯光隐藏页。

## 卡关排查

- 搜索有结果但只有索引：前置材料尚未读完，回到最近获得该词的档案检查页眉、年份和边注。
- 谜题按钮不可提交：通常是必需档案尚未打开，谜题上方会列出缺少的编号。
- `23-BLACK` 无法恢复：确认四份 `F01`—`F04` 方块分类都已打开。
- P8 证据被判无关：每题的两份证据必须不同，且都要直接支持该题关系。
- `ELEVATOR` 没有开放：确认 D08 三版照片、兔面秘密、金色方块秘密和 P8 都已完成。

