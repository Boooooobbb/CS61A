# CS61A: Structure and Interpretation of Computer Programs

本仓库是 UC Berkeley CS61A 课程的个人学习记录，包含课程的实验 (Labs)、作业 (Homework)、讨论 (Discussion) 和项目 (Projects)。

## 目录结构

```
CS61A/
├── labs/       # 实验练习
├── hws/        # 家庭作业
├── disc/       # 讨论材料
└── projects/   # 大型项目
```

## 内容概览

### Labs（实验）

| 实验 | 主题 |
|------|------|
| lab00 | Python 基础与环境配置 |
| lab01 | 控制流、条件语句、短路求值与调试 |
| lab02 | 高阶函数、Lambda 表达式与闭包 |

### Homework（作业）

| 作业 | 主题 |
|------|------|
| hw01 | Python 基础与函数 |

### Discussion（讨论）

| 讨论 | 内容 |
|------|------|
| disc01 | 课程入门讨论题 |

### Projects（项目）

#### 🎲 Hog（掷骰子游戏）

> **The Game of Hog** — 一个基于规则的双人骰子游戏模拟器。

**游戏规则亮点：**
- **Pig Out**：若任意一个骰子点数为 1，本轮得 1 分。
- **Free Bacon**：选择不掷骰子时，根据对手分数中 π 的位数获得额外分。
- **Swine Align**：若双方得分的最大公因数 ≥ 10，获得额外回合。
- **Pig Pass**：若本轮得分与对手得分之差小于 3，获得额外回合。

**核心文件：**

| 文件 | 说明 |
|------|------|
| `hog.py` | 游戏主逻辑（得分计算、回合模拟、完整对局） |
| `dice.py` | 骰子模拟工具 |
| `hog_gui.py` | 图形化界面服务 |
| `calc.py` | 辅助计算工具 |

**运行 GUI：**
```bash
cd projects/hog
python hog_gui.py
```

## 测试

本项目使用 [OK 自动评分工具](https://okpy.org/) 进行测试。

```bash
# 运行某个作业的测试，例如 hw01
cd hws/hw01
python ok

# 运行某个实验的测试，例如 lab01
cd labs/lab01
python ok
```

## 关于 CS61A

CS61A 是 UC Berkeley 计算机科学的入门课程，重点讲授：

- **函数式编程**（高阶函数、Lambda、递归）
- **面向对象编程**（类、继承、消息传递）
- **数据抽象**（列表、树、链表）
- **解释器设计**（Scheme 解释器项目）

课程官网：[https://cs61a.org](https://cs61a.org)
