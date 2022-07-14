# 概要 (Abstract)
- 連想ゲームwebアプリを作成する！
- Google ドキュメントの`note.gdoc`は必読！
- 参考文献にどんどん役に立ったものを記述してください！


# 注意点 (Attention)
- pushする前にpullを
- masterブランチで作業は行わない。個人作業が1区切りついたらmasterブランチに統合する。
- 秘密鍵など流出させてはいけないようなものは`.env`で環境変数で対処する
- 共有したい機密事項は`note.gdoc`で話し合う


# 環境 (Environment)


## VScode


### 環境構築
- 環境構築を文献[1]に従って行いましょう
    - 特にlaunch.jsonの作成する
- 文献[2]にしたがって`.vscode/`下に`.env`ファイルを作成しましょう


### 便利な拡張機能
- Git Graph (gitのバージョンの可視化)
- indent-rainbow (インデントが見やすくなる)
- Trailing Spaces (無駄な空白を可視化)


## バージョン
- `Python 3.8.8`
- `django==4.0.5`
- `psql (PostgreSQL) 14.4`


# 参考文献 (References)
1. [【VSCode】Django のデバッグ環境の構築手順](https://daeudaeu.com/vscode-django/)
1. [Djangoのサーバ起動をPycharmではなくVScode でやってみた件](https://qiita.com/souta1003/items/2d104e7ce2838e0ae232)
