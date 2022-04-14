# SlideShareが有料化されましたね！スライドが閲覧できなくなりましたがこれ使うとみれます拡張

Slide Shareが有料化されましたが，次のスライドを閲覧するボタンを押したときに指定したクラス(`limit-overlay`)の要素に対して`backdrop-filter: blur(5px);`を指定しているだけでした．

よってこの`limit-overlay`クラスの要素を削除するChrome拡張を作成しました