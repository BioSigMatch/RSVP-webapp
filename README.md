# RSVP Webアプリケーション

## これは何？
このWebアプリケーションは、「Rapid Serial Visual Presentation (RSVP)」システムを実装しています。ユーザーは、ターゲット画像およびノンターゲット画像を指定し、それらの画像を高速で連続的に表示することができます。また、提示周波数や計測時間などのパラメータを設定することが可能です。

## 機能
- **ターゲット画像とノンターゲット画像のアップロード**: ユーザーはターゲットおよびノンターゲット画像を選択し、それぞれの表示回数を設定できます。
- **提示周波数の設定**: 刺激呈示の周波数（Hz）を指定することができます。
- **安静開眼の計測時間**: 計測の時間を秒単位で指定できます。
- **画像シャッフル機能**: ターゲット画像が連続して表示されないようにする設定があります。
- **フルスクリーン表示**: 画像をフルスクリーンで表示可能です。
- **CSV保存**: 設定したデータや結果をCSV形式で保存することができます。

## 使い方
[デモページ](https://biosigmatch.github.io/RSVP-webapp/)
1. ターゲット画像およびノンターゲット画像をそれぞれ選択します。
2. 各画像の表示回数と、刺激呈示の周波数（Hz）、安静開眼の計測時間（秒）を設定します。
3. 必要に応じて「ターゲット画像を連続呈示しない」をチェックし、シャッフル機能を有効にします。
4. 「フルスクリーン表示」ボタンをクリックし、フルスクリーンモードにします。
5. 「スタート」ボタンを押して、画像の表示を開始します。
6. 結果を保存するには「CSVを保存」ボタンをクリックします。

## 必要要件
- ブラウザがJavaScriptに対応していること

## ライセンス
このプロジェクトはMITライセンスの下で提供されています。
