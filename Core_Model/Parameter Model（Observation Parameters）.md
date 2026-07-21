# 思考アルゴリズム骨格論

## Parameter Model（Observation Parameters）Ver.1

---

## Overview

本ドキュメントは、思考アルゴリズム骨格論（Skeleton Theory）における**観測パラメータモデル**を定義する。

本モデルの目的は、人間の認知処理を固定的な性格分類として扱うことではなく、情報入力に対する認知構造の**更新・保持・再構成プロセスの傾向**を観測することである。

各パラメータは、

* 能力評価
* 優劣判定
* 人格分類

を目的としない。

観測対象は、認知アルゴリズムにおける処理傾向である。

---

# 1. Basic Parameters

## 1.1 Update Pace (UP)

### Definition

既存の認知構造に対して、新しい情報や矛盾情報を受け取った際に、構造更新を開始する速度。

### Observation Targets

* 仮説修正までの速度
* 新情報への適応傾向
* 差分検出後の更新開始
* 更新頻度

### Tendency Examples

**Higher tendency:**

* 新しい情報を取り込みやすい
* 仮説修正が速い
* 環境変化への適応が速い

**Lower tendency:**

* 既存構造を維持しやすい
* 一貫性を重視する
* 更新に十分な根拠を求める

### Related Parameters

`SR / RF / CT`

---

## 1.2 Convergence Threshold (CT)

### Definition

情報探索や思考過程において、「一旦理解した」と判断する段階の傾向。

### Observation Targets

* 探索終了タイミング
* 仮説形成速度
* 不確実性保持

### Tendency Examples

**Higher tendency:**

* 多くの情報探索を行う
* 仮説確定を遅らせる
* 保留状態を維持する

**Lower tendency:**

* 早期に仮説形成する
* 暫定判断を利用する
* 行動へ移行しやすい

### Related Parameters

`UP / MC`

---

## 1.3 Structural Retention (SR)

### Definition

既存の認知構造を維持しながら、必要部分のみ更新する傾向。

### Observation Targets

* 長期的一貫性
* 更新後の安定性
* 局所修正能力

### Tendency Examples

**Higher tendency:**

* 構造を安定維持する
* 部分修正を行いやすい

**Lower tendency:**

* 全体的な再構築を行いやすい
* 構造が流動的

### Related Parameters

`UP / RF`

---

## 1.4 Reconstruction Flexibility (RF)

### Definition

既存構造を再編成し、新しい認知構造へ組み替える傾向。

### Observation Targets

* 異分野統合
* 発想転換
* モデル再設計

### Tendency Examples

**Higher tendency:**

* 新しい構造を形成しやすい
* 枠組み変更を行いやすい

**Lower tendency:**

* 既存構造を優先する
* 再設計頻度が低い

### Related Parameters

`SR / AL`

---

## 1.5 Abstraction Level Preference (AL)

### Definition

情報処理時に利用する抽象階層の傾向。

### Example Hierarchy

```text
具体
 ↓
事例
 ↓
パターン
 ↓
構造
 ↓
原理
 ↓
メタ原理
```

### Observation Targets

* 共通原理抽出
* 抽象化頻度
* 利用する思考階層

### Related Parameters

`RF`

---

# 2. Cognitive Resource Parameters

## 2.1 Automation (AU)

### Definition

処理が意識的制御なしに実行される傾向。

### Observation Targets

* 習慣化
* 熟達処理
* 無意識的処理

---

## 2.2 Semi Automation (SA)

### Definition

通常は自動化された処理に対し、状況変化時のみ意識的制御が介入する傾向。

### Observation Targets

* 状況変化への対応
* 自動処理から意識処理への切替

### Related Parameters

`AU`

---

## 2.3 Resource Allocation (RA)

### Definition

利用可能な認知資源をどの対象へ配分する傾向。

### Observation Targets

* 注意配分
* 優先順位
* 状況変化への対応

### Example Allocation Targets

* 観察
* 他者理解
* 問題解決
* 意味生成
* 未来予測

### Related Parameters

`PP`

---

## 2.4 Parallel Processing (PP)

### Definition

複数の認知処理を同時保持・進行する傾向。

### Observation Targets

* 複数情報の同時処理
* 会話中の状態把握
* 複数タスク間の処理

### Related Parameters

`RA`

---

# 3. Interpretation Principles

## 3.1 No Single Parameter Evaluation

単一パラメータによって個人を評価しない。

認知処理傾向は、複数パラメータの相互作用として解釈する。

---

## 3.2 Dynamic Processing Model

パラメータは固定的な人格属性ではない。

環境・目的・経験によって変化する認知処理傾向として扱う。

---

## 3.3 No Superiority Ranking

「高い」「低い」という表現は、性能評価ではなく処理傾向の方向性を示す。

---

# 4. Research Direction

### Future Research

今後の研究課題：

* パラメータ間相互作用の検証
* 観測方法の確立
* 状態変化との関連分析
* 実環境での再現性確認

---

# 5. License / Usage Note

本モデルは、認知アルゴリズムの観測枠組みを提供するものであり、人間の分類・評価・優劣判定を目的としない。

実装・応用に関する仕様は別途管理される。

