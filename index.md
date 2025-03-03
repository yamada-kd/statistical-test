# はじめに

```{only} html
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![made-with-numpy](https://img.shields.io/badge/Made%20with-NumPy-1f425f.svg)](https://numpy.org/)
[![made-with-matplotlib](https://img.shields.io/badge/Made%20with-Matplotlib-1f425f.svg)](https://matplotlib.org/)
```

## この教材について
この教材は東北大学データ科学国際共同大学院の自己学習教材です．利用するためには Google アカウントを持っている必要があります．

:::{panels}
:container:
:column: col-lg-6 px-2 py-2
:card:

---
**対象者**
^^^
これから統計検定についての知識を深めたい人．プログラミングの経験や統計学に関する知識はないことを前提にしています．

---
**使用するプログラミング言語**
^^^
プログラミング言語 [Python](https://www.python.org/) の利用方法を紹介します．Python は機械学習法を実装するための便利なライブラリを有する，データ科学を利用した研究開発に便利な言語です．

```python
#!/usr/bin/env python3

def main():
    print("Hello world")
     
if __name__ == "__main__":
    main()
```


:::

### このコンテンツで学ぶこと
このコンテンツの目的は，ウェブベースの計算環境である Jupyter Notebook（このウェブページを形作っているもの）を利用して，Python を利用して統計検定の概念を学ぶものです．

### この環境について
Jupyter Notebook は Python を実行するための環境です．メモを取りながら Python のコードを実行することができます．この環境は，Python プログラムがコマンドライン上で実行される実際の環境とは少し異なるのですが，Python プログラムがどのように動くかということを簡単に確認しながら学習することができます．

## 教材の利用方法
この教材は Google Colaboratory（グーグルコラボラトリー）を利用して作られています．グーグルコラボラトリーは Jupyter Notebook のファイルをウェブブラウザから使えるように Google が用意してくれたアプリです．各ページの上部にロケットのアイコン <i class="fa fa-rocket" aria-hidden="true"></i> があるのでこれをクリックして各ページのファイルを Google Colaboratory 上で開いて利用してください．

### 開始前に行うこと

```{hint}
グーグルコラボラトリー自体の一番上の「ファイル」をクリックし，さらにポップアップで出てくる項目から「ドライブにコピーを保存」をクリックし，自身のグーグルドライブにこのウェブページ全体のソースを保存します（グーグルのアカウントが必要です）．こうすることによって，自分で書いたプログラムを実行することができるようになります．また，メモ等を自由に以下のスペースに追加することができるようになります．
```

### コードセル

コードセルとは，Python のコードを書き込み実行するためのセルです．以下のような灰色のボックスで表示されていますす．ここにコードを書きます．実行はコードセルの左に表示される「実行ボタン」をクリックするか，コードセルを選択した状態で `Ctrl + Enter` を押します．環境によっては行番号が表示されていると思いますので注意してください（行番号の数字はプログラムの構成要素ではありません）．

```python
print("This is a code cell.")
```

### 進め方

上から順番に読み進めます．Python のコードが書かれていますので，それをコードセルに入力して実行します．コード内の値を変えたり，関数を変えたりして挙動を確かめてみてください．
