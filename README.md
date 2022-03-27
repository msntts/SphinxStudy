# 使い方
本リポジトリでは、Windows+VSCode+dockerでスライドを作成するための環境を用意しています。  
環境構築+スライド作成に関するタスクは ```.vscode/tasks.json``` に定義してあります。  
定義内容は以下の通りです。

| 用途                     | コマンド名                 | 処理                                                                             |
|---                       |--                          |--                                                                                |
| dockerイメージの作成     | create-sphinx-docker-image | sphinxという名前のコンテナイメージを作成                                         |
| sphinxプロジェクトの作成 | sphinx-quickstart          | 本リポジトリの ```project``` フォルダにsphinxプロジェクトを作成する              |
| スライドのビルド         | sphinx-build-slide         | スライドを作成する</br>スライドは ```project/_build/revealjs``` 以下に生成される |
