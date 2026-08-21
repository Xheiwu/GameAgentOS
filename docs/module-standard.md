# Game Module Standard / 游戏模块标准 / ゲームモジュール規格

## Purpose / 目的

A module is the smallest reusable game design unit that an AI agent can understand and implement.

模块是 AI Agent 可以理解、组合、实现的最小游戏设计单元。

モジュールとは AI エージェントが理解・組み合わせ・実装できる最小のゲーム設計単位です。

---

## Module Structure / 模块结构 / 構造

Each module contains:

每个模块包含：

- Experience goal / 玩家体验目标 / プレイヤー体験目標
- Input / 输入 / 入力
- Output / 输出 / 出力
- Logic flow / 逻辑流程 / ロジックフロー
- Parameters / 参数 / パラメータ
- Components / 组成部分 / 構成要素
- Dependencies / 依赖 / 依存関係
- Engine adapters / 引擎适配 / エンジン対応
- AI instructions / AI生成规则 / AI指示

---

## Design Principle / 设计原则 / 設計原則

Extract patterns, not copies.

提炼规律，而不是复制游戏。

ゲームをコピーするのではなく、設計パターンを抽出する。
