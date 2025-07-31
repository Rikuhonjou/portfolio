# ポートフォリオ

---
---

## Hit & Blow (C++ / Win32 API)

### 概要
4桁の数字を推理する脳トレゲーム。GUIは Windows API を用いて自作。
入力欄、決定ボタン、履歴表示などを全て Win32 API で構築。

### 実際の画面


### 技術ポイント
- C++17 + Win32 API による GUI構築（Edit, Button, ListBox）
- 入力制限(ES_SETLIMITTEXT)で1桁のみ、数字以外を拒否し後の処理を簡単に
- ヒット＆ブロー判定アルゴリズム(重複数字対応)
- std::chronoによるプレイ時間計測と表示
- 入力のバリデーションと履歴の動的更新

## 今後の改善案
- 難易度選択を可能
- マウスだけで操作

## 開発GitのURL
[Cpp_WindowGame](https://github.com/ho6ho6/Cpp_WindowGame)

---
---

## FPS_Chess

### 概要
チェスの駒をFPS視点で操作するアクション×戦略ゲーム。  
UnityRoomで公開中。チェスのルールとFPS操作を融合した新感覚ゲーム。

### 実際の画面
![FPS_Chess](./img/Chess_Debug.png)
![FPS_Chess](./img/Chess_play1.png)
![FPS_Chess](./img/Chess_play2.png)

### 技術ポイント
- Unity + C# による3Dゲーム開発
- 駒ごとの移動ロジックと攻撃判定の実装
- プレイヤー視点の切り替えとカメラ制御
- UI表示（ターン管理、勝敗判定）

### 工夫した点
- チェスのルールをベースにした独自のゲーム性
- 駒の種類ごとのスキルや移動制限の設計
- UnityRoomでの公開を想定した軽量化と操作性の調整

### 今後の改善案
- マルチプレイ対応（Photonなど）
- 駒のスキル演出強化（エフェクト、SE）
- ターン制のUI改善とチュートリアル追加

## 開発GitのURL
[ho66Games_FPSChess](https://github.com/ho6ho6/ho66Games_FPSChess.git)

## UnityRoom
[FPS_Chess](https://unityroom.com/games/ho66games_fpschess)

---
---

## 技術スタック
- C
- C++ (Win32 API)
- C#  (Unity, ゲームロジック, UI制御)
- Git / GitHub (ブランチ管理/README整備)
- Python

---
## その他
- GUIやゲームロジックを構築することが好きです。
- バグの検出・修正や、ユーザー目線の開発に粘り強く取り組むことを意識しています。
- 今後はネットワーク通信やAIを活かしたより躍動的なゲームにも挑戦したいです。

