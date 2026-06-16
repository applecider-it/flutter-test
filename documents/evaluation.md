# 評価

windowsだと、ファイルシステムの影響で遅くなるので難しい。

flutterを使うなら、素直にmacにするのが正解だと思う。

## mac移行時のコツ

windowsユーザーにとって、macは、そのままでは、かなり辛いと思うので、必要最小限の変更はセットで考えた方がいいと思う。

LinearMouse, Karabiner-Elements, Kekaをhomebrewからインストール。

Kekaのfinder拡張を有効化する。

マウスのスクロールの挙動はLinearMouseで直す。

Karabiner-Elementsで、caps lockとcmdを入れ替える。

設定 -> キーボード -> 入力ソース、でライブ変更を無効にして、caps lockを「入力モードの切り替え」に変える。

Karabiner-Elementsでは、デバイスごとに設定を自由に変えられるので、安いwindows向けの外付けキーボードも使えるようになる。

windowを閉じる時は、cmd+qを使う。

こうやって閉じないと、vscode, chromeなどでは、挙動がwindowsと異なってくる。

windowを最小化する時は、cmd+hを使う。

こうやって最小化しないと、Dockを圧迫していく。

ここまですれば、windowsとほとんど同じ操作感になると思う。

## windowsのボーダーライン

web開発は基本的にmacが無難だけど、wslがあるのでwindowsでもある程度は可能。

ただし、flutterのwslからのAndroidStudioの起動が使えないので難しい。

xcodeは、もちろん使えない。

electronは、macのほうが実装しやすい。

wslだけで完結するWebアプリケーションなら、windowsでも可能。

少しでもアプリがあるなら、macにした方が無難。

逆に、unityだとwindows。

## その他

windowsでキーコンフィグをいじりたい場合はPowerToys。

ただし、Karabiner-Elementsのように、デバイスごとの設定変更はできない。
