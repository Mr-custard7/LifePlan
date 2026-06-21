# ライフプラン シミュレーター

ファイナンシャルプランナー向けの30年間ライフプランシミュレーションアプリです。

## iPhoneアプリとして使う方法（PWA）

### ステップ1: GitHubにアップロード

1. [github.com](https://github.com) にログイン（アカウントがなければ無料登録）
2. 右上の「+」→「New repository」をクリック
3. Repository name に `lifeplan`（なんでもOK）と入力
4. **「Public」を選択**（GitHub Pagesに必要）
5. 「Create repository」をクリック
6. 「uploading an existing file」をクリック
7. このフォルダの中身をすべてドラッグ＆ドロップ
8. 「Commit changes」をクリック

### ステップ2: GitHub Pagesを有効にする

1. リポジトリの「Settings」タブを開く
2. 左メニューの「Pages」をクリック
3. Source を「Deploy from a branch」に設定
4. Branch を「main」→「/(root)」に設定
5. 「Save」をクリック
6. 数分待つと `https://あなたのユーザー名.github.io/lifeplan/` でアクセスできます

### ステップ3: iPhoneにインストール

1. iPhoneのSafariで上記URLを開く
2. 画面下の「共有」ボタン（□↑）をタップ
3. 「ホーム画面に追加」をタップ
4. 「追加」をタップ

→ ホーム画面にアイコンが追加され、アプリのように起動できます！

## 機能

- 家族構成の管理（名前・年齢）
- 月間収入（開始年・終了年・年増加率）
- 月間支出・年間支出の管理
- 年度別特別支出（住宅購入など）
- ライフイベントの手動登録
- 30年間の資産推移グラフ
- ライフプラン年表
- プランの保存・読み込み（localStorage）
- オフライン対応（Service Worker）
