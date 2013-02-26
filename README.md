xupdate_store
=============

X-update用のストア設定iniファイル

2013-02-26
X-update に登録している XoopsX/xupdate_store の各ストアの ini ファイルの取得オーバーヘッドを軽減するために、GitHub Pages を利用した静的ファイルに移行しました。
XoopsX/xupdate_store の各ストア ini の変更は、今後 gh-pages ブランチに行なっていただくこととなりますので、よろしくお願い致します。

【参考】 gh-pages 追跡ブランチのセットアップ (remote名が origin の場合)

git fetch origin
git checkout -b gh-pages origin/gh-pages

ファイル修正 & commit をする

初回のみ -u オプションつきで追跡設定する
git push -u origin gh-pages

次回からは
git pull
git push
でOKです。
