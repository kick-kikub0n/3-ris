【日本語バージョン】※The English version is provided below.

# 3'ris - 3盤面連動落ち物パズル

3つの独立した盤面を同時に操作する、ブラウザ向けの1人用落ち物パズルゲームです。

## ゲーム概要

中央・右・左の3盤面が、1つの入力で連動して動きます。
3盤面のうち、どれか1つでもブロック排出口の最上段まで積み上がるとゲームオーバーです。

各盤面には異なる向き・タイミングで各種ブロックが出現するため、3盤面全体を見ながら操作します。

## 遊び方

`index.html` をブラウザで開いてください。

公開サーバーで使用する場合は、`index.html` と `assets` フォルダを同じ階層に配置してください。

## 操作方法

### キーボード

- `←` / `→`: 左右移動
- `↑` / `X`: 右回転
- `Z`: 左回転
- `↓`: ソフトドロップ
- `Space`: ハードドロップ
- `C`: ホールド
- `P`: 一時停止
- `B`: 3列消去ボーナスの使用

### 画面操作

ゲーム画面下部（一部上部）のボタンから、移動・回転・ドロップ・ホールド・一時停止・ボーナス使用などを操作できます。

## 主な機能

- 3盤面連動型の落ち物パズルゲーム
- 日本語 / 英語対応
- キーボード・タッチ操作対応
- ホールド機能
- 特定条件によるライン消去ボーナス
- ハイスコア保存
- ゲーム内簡易説明ページ
- 効果音のON / OFF
- 落下ブロックの模様表示切替
- Web Audio API によるSE再生
- ゲーム中のBGM再生
- 盤面の積み上がりに応じたBGM速度変更

## 使用素材・クレジット

### 背景画像

- `assets/3'ris_bg1.png`
- ChatGPT 無料版を使用して生成・作成

### BGM

- `assets/3'ris_bgm1.ogg`
- `assets/3'ris_bgm2.ogg`
- 原曲: Google Gemini 無料版を使用して生成（MP3）
- OGG形式への変換: zaqro tools
  - https://zaqrobacca.com/tools/

※OGG形式への変換にzaqro toolsを使用しています。

各サービスの利用規約および生成物の利用条件を確認したうえで使用しています。

## ファイル構成

```text
3'ris/
├─ index.html
├─ README.md
└─ assets/
   ├─ 3'ris_bg1.png
   ├─ 3'ris_bgm1.ogg
   └─ 3'ris_bgm2.ogg
```

## 注意事項

- 音声が再生されない場合は、ゲーム開始ボタンを押したあとにサウンド設定を確認してください。
- 素材の利用条件や各サービスの規約が変更された場合は、公開前に再確認してください。


---
【English version】

# 3'ris - Three-Board Linked Falling-Block Puzzle

This is a browser-based, single-player falling-block puzzle game in which three independent boards are operated at the same time.

## Game Overview

The center, right, and left boards move together with a single input.
The game ends when any one of the three boards becomes filled up to the top row of its block outlet.

Different blocks appear on each board with different orientations and timings, so you need to watch all three boards while playing.

## How to Play

Open `index.html` in a web browser.

When using a public server, place `index.html` and the `assets` folder at the same directory level.

## Controls

### Keyboard

- `←` / `→`: Move left and right
- `↑` / `X`: Rotate clockwise
- `Z`: Rotate counterclockwise
- `↓`: Soft drop
- `Space`: Hard drop
- `C`: Hold
- `P`: Pause
- `B`: Use the three-line clear bonus

### On-Screen Controls

Use the buttons at the bottom of the game screen, and some buttons at the top, to move, rotate, drop, hold, pause, and use bonuses.

## Main Features

- Falling-block puzzle game with three linked boards
- Japanese / English support
- Keyboard and touch controls
- Hold function
- Line-clear bonuses under certain conditions
- High-score saving
- In-game simple instructions page
- Sound effects ON / OFF
- Pattern display toggle for falling blocks
- Sound effects generated with the Web Audio API
- BGM playback during gameplay
- BGM speed changes according to the stack height on the boards

## Assets and Credits

### Background Image

- `assets/3'ris_bg1.png`
- Generated and created using the free version of ChatGPT

### BGM

- `assets/3'ris_bgm1.ogg`
- `assets/3'ris_bgm2.ogg`
- Original tracks: generated using the free version of Google Gemini (MP3)
- OGG conversion: zaqro tools
  - https://zaqrobacca.com/tools/

Note: zaqro tools was used to convert the tracks to OGG format.

The terms of use for each service and the usage conditions for generated content have been reviewed before use.

## File Structure

```text
3'ris/
├─ index.html
├─ README.md
└─ assets/
   ├─ 3'ris_bg1.png
   ├─ 3'ris_bgm1.ogg
   └─ 3'ris_bgm2.ogg
```

## Notes

- If no sound is played, check the sound settings after pressing the game start button.
- Recheck the usage conditions for the assets and the terms of each service before publishing if they have changed.
