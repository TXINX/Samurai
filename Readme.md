# 墨影武士 · Samurai Showdown

简体中文 / English — 简洁的双语说明，适用于 GitHub 仓库首页显示。

---

## 目录

- [墨影武士 · Samurai Showdown](#墨影武士--samurai-showdown)
  - [目录](#目录)
  - [中文介绍](#中文介绍)
    - [操作指南](#操作指南)
    - [核心机制](#核心机制)
    - [如何开始游戏](#如何开始游戏)
  - [English Introduction](#english-introduction)
    - [Controls](#controls)
    - [Core Mechanics](#core-mechanics)
    - [How to Play](#how-to-play)

---

## 中文介绍

**墨影武士** 是一款极简水墨风格的快节奏动作游戏。你将扮演一名独行武士，守卫道场，对抗源源不断的浪人、精英影刺与强大的鬼大将。

游戏强调走位、节奏与资源管理：积攒“剑意”以释放必杀技，利用格挡与蓄力在关键时刻反击。

### 操作指南

| 按键 | 动作 | 说明 |
| :---: | :--- | :--- |
| **W A S D** | 移动 | 控制角色移动 |
| **鼠标左键 (点击)** | 拔刀斩 | 基础攻击，恢复少量耐力 |
| **鼠标左键 (长按)** | 蓄力 / 格挡 | 进入防御姿态，防御前方伤害；蓄满或受击后松开可释放强力剑气 |
| **鼠标右键** | 瞬步 | 快速冲刺并获得短暂无敌（消耗耐力） |
| **Q** | 狂风绝息斩 | 消耗 **30 剑意**：展开领域，短暂无敌并对领域内敌人造成大量伤害 |
| **E** | 月轮舞 | 消耗 **20 剑意**：发出旋转剑气并在终点形成吸附效果 |

### 核心机制

- **剑意系统**：击杀敌人可获得剑意（普通 +2、精英 +5、Boss +50），用于释放 Q/E 技能。
- **蓄力与弹反**：长按左键进入蓄力防御，若在蓄力期间成功格挡前方攻击，可触发“极意”并反击。
- **敌人类型**：
  - 🔴 浪人：普通成群敌人
  - 🟣 精英影刺：会瞬移偷袭
  - 🟡 鬼大将（Boss）：体型巨大，拥有霸体与震地技能

### 如何开始游戏

本作采用单文件架构（Single File Architecture），无需安装依赖或服务器。

1. 下载仓库中的 HTML 文件（例如 `main.html` 或 `samurai_showdown.html`）。
2. 使用现代浏览器（Chrome / Edge / Firefox）直接打开该文件。
3. 开始战斗！

---

## English Introduction

**Samurai Showdown** is a fast-paced action game with a minimalist ink-wash aesthetic. Play as a lone samurai defending your dojo against waves of Ronin, Elite Assassins, and the powerful Demon General.

The game focuses on movement, timing, and resource management: accumulate "Focus" to unleash ultimates and use parry mechanics to turn fights around.

### Controls

| Key | Action | Description |
| :---: | :--- | :--- |
| **W A S D** | Move | Character movement |
| **LMB (Click)** | Slash | Basic attack, regenerates a small amount of stamina |
| **LMB (Hold)** | Charge / Block | Enter guarding stance; immune to frontal damage. Release to fire a charged blade beam |
| **RMB** | Dash | Quick dash with brief i-frames (consumes stamina) |
| **Q** | Wind Slash (Ult) | Cost: **30 Focus** — create a domain, become invincible, and rapidly slash enemies inside |
| **E** | Moon Dance | Cost: **20 Focus** — launch a wide spinning blade wave that pulls enemies in |

### Core Mechanics

- **Focus system**: Gain Focus by killing enemies (Normal +2, Elite +5, Boss +50). Use Focus to cast Q/E skills.
- **Charge & Parry**: Hold LMB to block. Successfully blocking frontal attacks while charging triggers a "Perfect Parry" and allows a powerful counter.
- **Enemies**:
  - 🔴 Ronin — basic swarming enemies
  - 🟣 Elite Assassin — teleports behind the player for surprise attacks
  - 🟡 Demon General (Boss) — large, armored, uses shockwave attacks

### How to Play

This game is a single-file HTML project. No installation or server required.

1. Download the HTML file from this repository (e.g., `main.html`).
2. Open it in any modern web browser (Chrome / Edge / Firefox recommended).
3. Enjoy the fight!

---

_Created with HTML5 Canvas & JavaScript._