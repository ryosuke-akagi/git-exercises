# 使用したコマンド

### クローン

1. ##### "Z:\実習\github"フォルダを作成する。
    ```
    cd /d Z:/実習
    mkdir github
    ```
1. ##### 上記フォルダにフォークしたリポジトリをクローンする。
    ```
    cd github
    git clone <フォーク先のURL>
    ```
1. ##### "cmd.md"ファイルを作成し、使用したコマンドをMarkDown形式でわかりやすく記載する。
    ```
    type nul > cmd.md
    ```
---

### プッシュ

1. ##### 自身のWindowsログイン名のブランチを作成し切り替える。
    ```
    git switch -c r_akagi
    ```
1. ##### 自身の名前(フルネーム)のMarkDownファイルを作成し、自己紹介を記入する。
    ```
    type nul > Ryosuke_Akagi.md
    ```
1. ##### リポジトリへプッシュする。
    ```
    git add Ryosuke_Akagi.md
    git commit -m "自己紹介を作成"
    git push origin r_akagi
    ```
---