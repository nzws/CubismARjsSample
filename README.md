# Cubism SDK AR.js Samples

Cubism SDK For JavaScript の AR.js を使ったサンプルです。  

マーカーにロゴ画像を使う例と QR コードを使う例の2種類を用意しています。

各サンプルに紐付くマーカーを印刷し、サンプルページを開いて、カメラでマーカーを映すとモデルが表示されます。

- [ロゴ画像をマーカーにしたサンプル](https://live2d.github.io/CubismARjsSample/)
 - [Marker](https://live2d.github.io/CubismARjsSample/assets/logo_marker.png)

- [サンプルページへの QR コード自体をマーカーにしたサンプル](https://live2d.github.io/CubismARjsSample/qr_marker.html)
 - [Marker](https://live2d.github.io/CubismARjsSample/assets/qr_marker.png)

## オリジナルのモデルを使うには？

1. assets フォルダの moc3 や json、テクスチャを差し替えます

2. js フォルダの pixiAframeAR.js をテキスト形式で開き、各ファイルへのパスを差し替えたものに変更します

3. オリジナルのモデルが表示されるようになります

## オリジナルのマーカーを使うには？

1. [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) を開きます

2. UPLOAD ボタンを押し、マーカーにしたい画像を選択します

3. DOWNLOAD ボタンを押し、patt ファイルを assets フォルダに保存します

4. html ファイルの a-marker タグにある url を patt ファイルのパスに変更します

5. 画面中央に表示されている黒枠に囲まれた画像がマーカーとして使えるようになります

## オリジナルのQRコードを使うには？

QR コードの作成方法に指定はありません。

ウェブ上にQRコード生成サービスが多数提供されていますので、お好きなものをお使いください。

**QRコードを [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) でマーカー画像に指定することもできます。**

## 簡単に試してみたい

下記の方法を使うとサーバを用意せずに試すことができます

1. Google Chrome に [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=ja) アドオンを追加します

2. Web Server for Chrome を実行し、CHOOSE FOLDER ボタンで CubismARjsSample のあるフォルダを選択します

3. ブラウザから [http://127.0.0.1:8887/CubismARjsSample/](http://127.0.0.1:8887/CubismARjsSample/) にアクセスします

4. カメラで [マーカー](https://live2d.github.io/CubismARjsSample/assets/logo_marker.png) を映すとモデルが表示されます

## 注意事項

オリジナルのマーカーを使うために、AR.jsのコードを部分的に変更しています。詳しくは [こちら](https://github.com/wimvdc/AR.js/commit/950e82db6d0c3851647d429282c5ade52ee95891) をご覧ください。

aframe-ar.js を他のバージョンに差し替える際はご注意ください。

## TODO

- 解像度の動的な変更
- バックカメラの指定
- カメラ方向への視線追従機能
- タップでのモーション再生
- 設定値の分離（jsonファイル？）

## ライセンス

このサンプルコードは MIT ライセンスで提供しています。

また、 AR.js に含まれる ARToolKit.js は LGPLv3 ライセンスとなっています。

詳細については、jsartoolkit5 ライセンスと AR.js ライセンスを確認してください。

jsartoolkit5 is under LGPLv3 license and additional permission.
For legal details, be sure to check jsartoolkit5 license and AR.js license.

[jsartoolkit5 license](https://github.com/artoolkit/jsartoolkit5/blob/master/LICENSE.txt)

[AR.js license](https://github.com/jeromeetienne/AR.js/blob/master/LICENSE.txt)
