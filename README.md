# niconicodic-chrome-editable

Chromeでニコニコ大百科が編集できない問題に**暫定的に**対応するChrome拡張です。


**warning: このChrome拡張は、Chromeの保護機能を無理やり無効化して編集できるようにしています。そのため、大百科側にXSSなどのセキュリティーホールがあった場合、それを未然に防ぐ事ができなくなるかもしれません。これを使って何か悪影響が起きても知りません。**

Chrome以外で動くかはわかりませんが、Chromium系列なら動くんじゃないでしょうか。

## なにをしてるの

`https://dic.nicovideo.jp/p/*`に`X-XSS-Protection: 0`を注入してるだけ

## thanks

- https://github.com/EzoeRyou/inject-mathjax (リクエストにヘッダーを注入する方法を参考にしました)