# VSCodeのショートカット


## サイドバー

### サイドバー表示トグル
	Ctrl + B

### エクスプローラー表示トグル
	Ctrl + Shift + E

### フォルダーを開く
	Ctrl + K & Ctrl + O


## コマンド系

### ファイル内のシンボルへ移動
	Ctrl + R

### .mdファイルのプレビュー表示
    Ctrl + M ＆ Ctrl + D

### コマンドパレット表示
    F1
	Ctrl + Shift + P

## 表示系

### 上へスクロール（マウスホール上）
	Ctrl + Alt + PageUp

### 下へスクロール（マウスホール下）
	Ctrl + Alt + PageDown

### 上へ1行ずつスクロール
	Shift + Alt + PageUp

### 下へ1行ずつスクロール
	Shift + Alt + PageDown

### 次のハイライトのシンボルへジャンプ
	Alt + PageDown
### 前のハイライトのシンボルへジャンプ
	Alt + PageUp

## 操作系

### キーボードショートカット チートリスト　
    Ctrl + K & Ctrl + S

### カーソルを複数選択　
    Alt + ↑
    Alt + ↓
    Ctrl + 左クリック　（個別に複数）
    Ctrl + Shift + 左クリック　（一括範囲）

### カーソル行を移動
    Ctrl + Shift + ↑
    Ctrl + Shift + ↓

### 選択範囲を複製
    Ctrl + Shift + D

### 選択範囲をタグで囲む
    Shift + Alt + W

### 改行
    Shift + Enter

### インデントをタブに切り替え
    Ctrl + ] + Tab

### インデントをスペースに切り替え
    Ctrl + ] + Space


### 検索 次の検索結果にフォーカス
    F4

### 検索 次の検索結果にフォーカス
    Shift + F4

### 検索 正規表現使用トグル
    Alt + R

### フォーマット 選択範囲
    Alt + F + Alt + F

### HTMLLint エラーパネル表示
    Ctrl + Shift + M

### 次のエラーへ移動
    F8

### 前のエラーへ移動
    Shift + F8


## ターミナル
### ターミナルパネル表示
	Ctrl + ＠

## タスクランナー Gulp
### タスクの構成
Ctrl + Shift + P → Configure Task → 構成するタスクを選択 → ルートフォルダに.vscodeとtasks.jsonが出力される
※タスクの構成が無い状態で初回タスク（Gulp）を実行すると自動的に ルートフォルダに.vscodeとtasks.jsonが出力される


### タスク実行
	Ctrl + Alt + R

### タスク終了
	Ctrl + Alt + Q

## デバッグ
### デバッグの構成

（デバッグしたいファイルを開いた状態で）Ctrl + Shift + D → 歯車アイコンを選択 → ルートフォルダに「.vscode」フォルダが作成され、その中に launch.json が出力される
launch.json の中のデバッグしたいファイルパスがあっていないときがあるので、ファイルパスあわせる

（/**/での指定は出来なかったので、パス指定する）

例：

	"program": "${workspaceFolder}/source/directory/directory/js/base.js"


### デバッグ表示トグル
	Ctrl + Shift + D

### デバッグコンソール表示
	Ctrl + Shift + Y


### デバック開始
    F5

### デバック停止
    Shift + F5

### デバックなしで開始
    Ctrl + F5

### デバック再起動
    Ctrl + Shift + F5

### 続行
    F5

### 一時停止
    F6

### ステップオーバー
    F10

### ステップイン
    F11

### ステップアウト
    Ctrl + F11

### デバッグコンソールビューにカーソル選択
	Ctrl + \ (ろ)

### コンソールのクリア
	Ctrl + space + \ (ろ)

### ブレイクポイントトグル
    F9

## Emmet

### 数値を1ずつ増やす
	Ctrl + ↑

### 数値を1ずつ減らす
	Ctrl + ↓

### 数値を10ずつ増やす
	Ctrl + Alt + ↑

### 数値を10ずつ減らす
	Ctrl + Alt + ↓

### 数値を0.1ずつ増やす
	Ctrl + Shift + ↑

### 数値を0.1ずつ減らす
	Ctrl + Shift + ↓


## 拡張機能

### Live Server
ライブサーバーを起動し、ライブリロードできる
ルートからのパス設定でも表示可能
※ファイル単体で実行すると動作しないため、必ずフォルダを開く

ライブサーバースタート

	Win：Ctrl + L ＆ Ctrl + S
	Mac：command + L ＆ command + S

ライブサーバーストップ

	Win：Ctrl + L ＆ Ctrl + Q
	Mac：command + L ＆ command + Q

ライブサーバーを起動するWorkspaceを変更

	Win：Ctrl + L ＆ Ctrl + W

参照：<br>
https://www.mitsue.co.jp/knowledge/blog/frontend/201810/02_1329.html
https://www.nxworld.net/services-resource/vscode-extension-live-server.html



### Force Code
Force Code Menu

	Win : Ctrl + Alt + F
