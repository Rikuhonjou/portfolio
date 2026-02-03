# ポートフォリオ

---
## 取り組んでいるプログラミング作品への開発Git
### C++とWin32を使ってミニゲームエンジン : [minigame_engine](https://github.com/ho6ho6/minigame_engine) </br>
[ミニゲームエンジンの解説動画]https://youtu.be/hTtWyzAT5uM </br>
[ミニゲームエンジン内容確認動画]https://youtu.be/BEkCKfG-fzU </br>
</br>

### Unityで一人称チェス : [ho66Games_FPSChess](https://github.com/ho6ho6/Chess_FistPerson) </br>
[一人称チェスゲーム内容確認動画]https://youtu.be/s0ZbeJykjSQ </br>
[一人称チェス作品解説動画]https://youtu.be/TX8dBKSlUoM </br>

---
---

# ミニゲームエンジン (C++ / Win32 API / DirectX11 / ImGui)

## 概要
Unityを目標にした、ソースコードを書かないゲームエンジンを作成中。</br>
予め、オブジェクトには各キーやマウスを設定しておき、ユーザーはチェックを入れどのキーに対応させるかを考えるだけで良いものにする。</br>
任意のオブジェクトにComponentを追加し、数値を入力するだけでキー入力やフラグなどの操作が可能になっている。</br>
基本は Win32 API を使い、現状はWindows用に構築しています。<br>
多くの人が直感的に操作できることを重視しているため、想定動作環境は </br>
CPU:AMD Athlon Shilver 3050U with Radeon Graphics </br>
メモリ:8.0GB </br>
GPU:AMD Radeon(TM) Graphics (CPUに内臓されているものを想定)</br>

## 実際の画面

### 現状-主要Component機能を実装し、Key割り当ての対応を実装した。
![ゲームエンジン](./img/minigame_engine10.png)

## 今後の予定
- 各Component機能を実装し、細かい不具合の修正を行う。</br>
- ゲームをビルドした際に、実際のゲーム画面となるwindow_gameを実装する。</br>

## 開発Git
[minigame_engine](https://github.com/ho6ho6/minigame_engine)

---
---

# FPS_Chess (Unity)

## 概要
チェスの駒をFPS視点で操作するアクション×戦略ゲーム。  </br>
UnityRoomで公開中。チェスのルールとFPS操作を融合した新感覚ゲーム。

## 実際の画面

### デバック画面
![FPS_Chess](./img/Chess_Debug.png)

### ルーク視点
![FPS_Chess](./img/Chess_play1.png)

### キング視点
![FPS_Chess](./img/Chess_play2.png)

## 技術ポイント
- Unity + C# による3Dゲーム開発
- 駒ごとの移動ロジックと攻撃判定の実装
- プレイヤー視点の切り替えとカメラ制御
- UI表示（ターン管理、勝敗判定）

## 工夫した点
- チェスのルールをベースにした独自のゲーム性
- 駒の種類ごとのスキルや移動制限の設計
- UnityRoomでの公開を想定した軽量化と操作性の調整
- ゲーム全体の雰囲気・プレイヤーの気を散らさない程度のBGMの作成

## 今後の改善案
- マルチプレイ対応（Photonなど）
- UIの華やかさを追加を検討

## 作成した音源
[🎵 title.mp3 を聴く](./sound/タイトルBGM.mp3) </br>
[🎵 game.mp3 を聴く](./sound/対戦BGM.mp3) </br>
[🎵 result.mp3 を聴く](./sound/結果画面.mp3) </br>

## 開発GitのURL
[ho66Games_FPSChess](https://github.com/ho6ho6/Chess_FistPerson)

## UnityRoom
[注意] 作り直した一人称チェスではUnity6で作成していたため、Buildの際にWeb GLが非対応になっており </br>
アップデートができず、旧作の一人称チェスになっております。 </br>
Unity 2022年のもので再度作り、Webでも遊べるように現在は、取り組んでいます。 </br>
[FPS_Chess](https://unityroom.com/games/ho66games_fpschess)

---
---

## 技術スタック
- C
- C++ (Win32 API)
- C#  (Unity, ゲームロジック, UI制御)
- Git / GitHub (ブランチ管理/README整備)

---
---

# 過去に作成したキャラクタや2D・3Dグラフィックス
## 2Dシューティングゲームに作成したAssets (グラディウスを参考にして作成しました)
1. 星間飛行 </br>
![2DGR](./img/design/stage1_道中.png)
2. 敵の本拠地 </br>
![2DGR](./img/design/stage3_2.png)

### 自キャラ・敵キャラ </br> 
![2DGR](./img/design/自機.png)
![2DGR](./img/design/敵弾.png)

## 3Dグラフィックス (リミナルスペースと呼ばれる空間のモデリングを中心に行っています) </br>
1. プール空間 </br>
![3DGR](./img/design/liminal_world_pool.png)
2. 子供部屋 </br>
![3DGR](./img/design/liminal_world_space.png)
3. 曇り空の夜 </br>
![3DGR](./img/design/liminal_world_wheat.png)

---
---

## その他
- GUIやゲームロジックを構築することが好きです。
- バグの検出・修正や、ユーザー目線の開発に粘り強く取り組むことを意識しています。
- 今後はネットワーク通信やAIを活かしたより躍動的なゲームにも挑戦したいです。
- 新しい着眼点をもってゲーム制作や、プログラミングに取り組むことを心掛けています。

