# 環境構築

```
sudo apt install texlive-lang-cjk xdvik-ja evince
sudo apt install texlive-fonts-recommended texlive-fonts-extra
```

# How to use
```
platex hoge.tex  # texファイルをdviファイルに変換
dvipdfmx hoge.dvi  # dviファイルをpdfに変換
evince hoge.pdf &  # pdfファイルを開く
```
