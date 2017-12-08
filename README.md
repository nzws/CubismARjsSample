# Cubism SDK AR.js Samples

Cubism SDK For JavaScript の AR.js を使ったサンプルです。  

マーカーにロゴ画像を使う例と QR コードを使う例の2種類を用意しています。

- [Logo Marker Sample](https://live2d.github.io/CubismARjsSample/)

- [QR code Marker Sample](https://live2d.github.io/CubismARjsSample/qr_marker.html)

## オリジナルのモデルを使うには？

1. assets フォルダの moc3 や json、テクスチャを差し替えます

2. js フォルダの pixiAframeAR.js をテキスト形式で開き、各ファイルへのパスを差し替えたものに変更します

## オリジナルのマーカーを使うには？

1. [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) を開きます

2. UPLOAD ボタンを押し、マーカーにしたい画像を選択します

3. DOWNLOAD ボタンを押し、patt ファイルを assets フォルダに保存します

4. html ファイルの a-marker タグにある url を patt ファイルのパスに変更します

5. 画面中央に表示されている黒枠に囲まれた画像を紙などに印刷し、マーカーとしてお使いください。

## オリジナルのQRコードを使うには？

QR コードの作成方法に指定はありません。

ウェブ上にQRコード生成サービスが多数提供されていますので、お好きなものをお使いください。

**QRコードを [AR.js Marker Training](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) でマーカー画像に指定することもできます。**

## 注意事項

オリジナルのマーカーを使うために、AR.jsのコードを部分的に変更しています。詳しくは [こちら](https://github.com/wimvdc/AR.js/commit/950e82db6d0c3851647d429282c5ade52ee95891) をご覧ください。

aframe-ar.js を他のバージョンに差し替える際はご注意ください。

## ライセンス

このサンプルコードは MIT ライセンスで提供しています。

また、 AR.js に含まれる ARToolKit.js は LGPLv3 ライセンスとなっています。

詳細については、jsartoolkit5 ライセンスと AR.js ライセンスを確認してください。

jsartoolkit5 is under LGPLv3 license and additional permission.
For legal details, be sure to check jsartoolkit5 license and AR.js license.

[jsartoolkit5 license](https://github.com/artoolkit/jsartoolkit5/blob/master/LICENSE.txt)

[AR.js license](https://github.com/jeromeetienne/AR.js/blob/master/LICENSE.txt)
