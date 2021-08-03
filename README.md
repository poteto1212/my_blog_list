# 今回やる事
- プロジェクトの作成
- サーバーの試験起動
- 日本語化
- モジュールインストール
- githubへの公開

# 目標成果物
ここではこれからアプリ作成を行っていくためのプラットフォームを作成していきます。本記事での最終目標の画面は以下のようになります。
![image](https://user-images.githubusercontent.com/79962572/127957935-eb279fee-c047-4505-889b-73f32a2b9a15.png)

# プロジェクト作成コマンド

ターミナルをクリックするとホームディレクトリが開きます
in ホームディレクトリ
```
django-admin startproject my_blog_list
```
my_blog_listという名前のプロジェクトを作成しろと言った命令コマンドになります。

上記ののコマンドによって
![image](https://user-images.githubusercontent.com/79962572/127958264-1db7194d-9c32-4ebf-a092-d07dd10e6807.png)
のような階層のフォルダーが自動生成されます。

その後
```
cd my_blog_site
```
基本的にコマンドによる命令ができるのは命令対象となるファイルと自身が同じフォルダー下にいる時になります。
cd <フォルダー名>
コマンドは指定したフォルダーに自身を移動させるコマンドになります。
このコマンドによってmy_blog_siteファイルに移り、その下にあるmanage.pyファイル等にコマンド命令が出来る様になります。




## 編集ファイルの一覧まとめ
