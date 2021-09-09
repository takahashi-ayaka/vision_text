# vision_text
目標管理(新スキル学習)のリポジトリ
## 要約
文字認識(OCR)アプリケーションを作成
スマートフォンのカメラを使用して文字認識を行ない、認識した文字を画面に表示する
## 画面構成
* トップ画面
　・文字表示画面としても使用
* 写真確認画面
## 用意するもの
* macOS
* Xcode
* Swift
* iPhone
## 実行前の準備
* macとiPhoneをケーブルで接続する
* プロジェクトのGeneralにあるBundleIdentifierを変更する
* 下記のサイトを実施する
https://i-app-tec.com/ios/device-test.html
https://qiita.com/natsumo/items/3f1dd0e7f5471bd4b7d9
https://qiita.com/Shinji-Hashimoto/items/0660158b2336329af635
* 証明書の作成等(その他方法)
https://dev.classmethod.jp/articles/xcode-8-signing/
* Xcodeのバージョンと実機のOSバージョンが異なる場合
https://sussan-po.com/2019/10/12/new-ios-device/
## 実行方法
実行前の準備でビルドが成功したら実機にアプリが追加されているので起動する
## 現在のディレクトリ・ファイル構成
```
.
├── README.md
├── VisionFrameworkTest.xcodeproj
├── VisionFrameworkTest
│   ├── AppDelegate.swift
│   ├── Info.plist
│   ├── SceneDelegate.swift
│   ├── ViewController.swift
│   ├── Assets.xcassets
│   │   ├── Applcon.appiconset
│   │   │   ├── Contents.json
│   │   ├── Contents.json
│   ├── Base.lproj
│   │   ├── LaunchScreen.storyboard
│   │   ├── Main.storyboard
```
## 解説など
## その他
