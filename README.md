# NuGetCustomBuilder readme

 NuGet パッケージに targets と props の MsBuild プロジェクトファイルを組み込んで
カスタムビルド処理をパッケージ化する為のプロジェクトテンプレートです。


 このプロジェクトテンプレートを元にプロジェクトを作成すると、 Nuget パッケージの build 配下に targets および、propsファイルを配置した NuGetパッケージが生成されるプロジェクトが作成されます。

 適当に targets / props を設定して NuGet パッケージを作成すると、 NuGet パッケージのインストールによって指定のビルド時動作が行われるようになります。

## インストール

 [リリース物](http://github.com/kazuk/NuGetCustomBuilder/releases) を取得しプロジェクトテンプレートフォルダに配置します。

 プロジェクトテンプレートフォルダは一般に、ドキュメントフォルダのVisual Studio 2012配下に Templates/ProjectTemplatesとして存在します。

## 使い方

 [v1.0リリース](https://github.com/kazuk/NuGetCustomBuilder/releases/tag/v1.0) のドキュメントに画像とかそこそこついています。

 普通に NuGetCustomBuilder プロジェクトテンプレートを選択して、プロジェクトを作り、ビルドすればターゲットディレクトリに NuGetパッケージが作られます。

 あとは NuGet でパッケージを取得してもらえばビルド時処理を追加できますし、アンインストールで外せるはずです。

 csproj のいじり方解らない人に、そんなこと覚えなくてもいいよ、永遠に知らんでいいよ。ができるという事ですね。
