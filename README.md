# [Fix Twitter/X Link](https://app.nqme.net/FixTwLink/)

自分用です。

スマホ使用時にTwitter(現X)の共有機能のリンクをDiscordに貼るのをラクにするためのWebアプリです。ついでにYouTubeのリンクにも対応させました。

無駄にGitHub Actionsでhtmlのサイズを最小化させています。2.9KB -> 1.8KBになりました。[wilsonzlin/minify-html](https://github.com/wilsonzlin/minify-html)をお借りしています。

## 機能 / feature
- TwitterとXのリンクは、fxtwitter.comとfixupx.comに変換してクエリを削除します。
  - This tool converts Twitter and X links to fxtwitter.com and fixupx.com, removing any query parameters.
- YouTubeのリンクから余分なクエリを削除します。
  - It also removes unnecessary query parameters from YouTube links.


## 使い方 / Usage
- Pasteボタンを押してクリップボードの文字列を入力欄に貼り付けるか、直接URLを入力してください。
  - Press "Paste" button to paste the string from the clipboard, or enter the URL directly.
- Copyボタンを押すと出力欄の文字列がクリップボードにコピーされます。
  - Press "Copy" button to copy the string from this app to the clipboard.