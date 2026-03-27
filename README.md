# ピンポイントで色を取るやつ（PWA）

カメラをかざして、狙った場所の色をHEXとかRGBで抜くためのアプリです。
ググって見つかるツールだといちいち画像をアップロードしないといけなかったりするのでWEBですぐみられるようにしました。

## 🚀 Try it here ここでお試し
**[https://alhms.github.io/color-picker-for-web/](https://alhms.github.io/color-picker-for-web/)**

## 特徴
- 起動したらすぐカメラが出る（これ大事）
- 画面真ん中のピンの先っちょで色を取る
- ~~明るさと色温度をスライダーでいじれる（実物の色に近づける用）~~ 実装予定
- シャッター押すと勝手にクリップボードにコピーされる
- HEXとRGBはボタンで切り替え。切り替えた時もコピーされる
- PWA対応。スマホのホーム画面に入れて使うのが正解

## 使い方
ブラウザですぐ使えます。
カメラが勝手に明るさを変えちゃうので、肉眼の色と合わない時に手動で調整するためにスライダーを付けました。

## ファイル
- index.html: 全部入り。
- manifest.json: アイコンとかの設定。
- sw.js: オフラインでも動くようにするおまじない。

## ライセンス
MITで。好きに使ってください。

# Quick Pinpoint Color Picker (PWA)

A simple web-based tool to grab HEX or RGB colors just by pointing your camera. 
I was tired of tools that make you upload a photo first, so I made this to work instantly in your web browser.

## Features
- Opens the camera immediately in your browser (This is the most important part).
- Pick colors precisely using the tip of the pin in the center.
- ~~Sliders to tweak brightness and warmth so the screen matches what your eyes see.
- Auto-copies to clipboard when you hit the shutter.
- Toggle between HEX and RGB (copies again on toggle).
- It's a PWA, so you can also "Add to Home Screen" if you want to use it like a native app.

## How to use
Just open the URL in your mobile browser. 
Since cameras tend to auto-adjust colors, I added sliders so you can manually adjust the preview until it looks like the real-world object.

## Files
- index.html: Everything is in here.
- manifest.json: Icons and PWA settings.
- sw.js: Service worker magic for offline support.

## License
MIT. Feel free to use it.

Copyright (c) 2026 ALHMS
