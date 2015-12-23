# helm-img

画像のURLやファイルパスのリストを受け取り、helmバッファに画像を表示するためのライブラリです。

サンプルとして以下のコマンドを同梱しています。

* helm-img-dir.el  
指定したディレクトリにある画像ファイルをhelmバッファに表示します。
* helm-img-bing.el  
Bing Search APIを使用して画像検索した結果をhelmバッファに表示します。使用する際はあらかじめ`helm-img-bing-account-key`にMicorsoftアカウントのアカウントキーをセットする必要があります。
