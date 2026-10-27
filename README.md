# Smash Hit — 可无视的玻璃障碍（两处观察）

Two player observations on glass obstacles that can be passed without spending balls.

> 观察者：本人（Mac / iOS 版 · 经典模式）
> 日期：2026-10-27
> 说明：这是玩出来的观察，不是拆包结论。欢迎指正。

---

## 中文

### 1. 第二关：摆动的玻璃面板

第二关里有一组**三块一起摆动的正方形玻璃**，它们是**必须打掉**的。

另外还有一组**长方形玻璃**也在摆动 —— 但**它们可以完全不管**。它们的摆动**不会把自己送进玩家路径**，所以不会触发受击判定。打它们纯粹是浪费球。

> 注意区分：同一关里「三块一起摆动的正方形」和「摆动的长方形」是两回事 —— 前者要打，后者不用。

### 2. 第八关：斜着的长条玻璃

斜向的长条玻璃**可以等靠近再打**。近距离时，**只打掉挡住当前路径的那一块**就够了，其余的通常不会影响通过。

---

## English

### 1) Stage 2 — swinging glass panels

Stage 2 has a group of three **square** panels swinging together; those still have to be destroyed.

Separately, the **rectangular** panels also swing, but they can be passed **without breaking them**. Their swing does not put them into the player's path, so no hit judgement is triggered — ammo spent on the rectangular ones is wasted.

### 2) Stage 8 — diagonal long glass strips

The diagonal strips can be left alone until you are closer. At close range, breaking the single strip that currently blocks your path is enough; the others usually don't obstruct the player.

---

## Context

- Observed in **Classic mode**, Apple platform (macOS / iOS build).
- Not systematically tested in Training or Frenzy mode.
- Related: the Smash Hit Wiki notes for Stage 1 DNA that *"some DNA pieces can be passed without breaking"*, and that classic mode also contains glass that needn't be broken. These two observations are the same family of cases — obstacles that carry no path judgement.
- The old `Smashing-Tech/docs` GitHub repo (2023) is archived/read-only and has issues disabled, so this note lives here instead.

## 想继续补

如果你也玩，欢迎在 Issues 里补充：
- 其它关里「摆着但其实挡不到路」的玻璃
- 各模式下（训练/狂乱）是否一致
- 具体版本号与复现步骤
