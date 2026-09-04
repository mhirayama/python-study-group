# Pythonで学ぶ データ分析・機械学習 勉強会

Pythonを実際に動かしながら、データ分析や機械学習の基本を体験する全4回の勉強会です。

プログラミングやデータ分析を最初から詳しく学ぶのではなく、

**説明する → コードを動かす → 結果を見る → 考えてみる**

という流れで、少人数でゆっくり進めていきます。

---

## 全4回の構成

### 第1回　Google Colabを使って、Pythonを始めよう

Google Colabを使って、ブラウザ上でPythonを実際に動かしてみます。

Pythonの基本的な書き方を体験しながら、変数や計算、文字列、リスト、条件分岐、繰り返しなど、Pythonを使うための基本を学びます。

最後に、Pythonで簡単なデータを扱ってみます。

**主な内容**

1. Pythonを動かす

2. Pythonの基本的な書き方を試す

3. 変数・計算・文字列・リストを使う

4. 条件分岐・繰り返しを体験する

5. Pythonで簡単なデータを扱う

**教材**

`01_python/lesson01.ipynb`

→ **[Google Colabで開く](https://colab.research.google.com/github/mhirayama/python-study-group/blob/main/01_python/lesson01.ipynb)**

---

### 第2回　pandasでデータを扱ってみよう

データ分析は、まずデータを知ることから始まります。

Pythonのライブラリ「pandas」を使って、CSVファイルからデータを読み込みます。

読み込んだデータの内容を確認し、必要なデータを整理しながら、最後にデータを集計してみます。

表形式のデータをPythonで扱う基本的な方法を学びながら、データ分析の流れを体験します。

**主な内容**

1. データを読み込む

2. データを確認する

3. データを整理する

4. データを絞り込む

5. データを集計する

**教材**

`02_pandas/lesson02_pandas.ipynb`

→ **[Google Colabで開く](https://colab.research.google.com/github/mhirayama/python-study-group/blob/main/02_pandas/lesson02_pandas.ipynb)**

---

### 第3回　Matplotlibでデータをグラフにしてみよう

データをグラフにすると、数字だけでは見えなかったことが見えてきます。

Pythonのライブラリ「Matplotlib」を使って、第2回で扱ったpandasのデータをグラフにしてみます。

棒グラフや折れ線グラフを描きながら、データを視覚的に捉える方法を学びます。

グラフをつくるだけでなく、そこからデータの特徴や変化を読み取り、データを「見る」ことを体験します。

**主な内容**

1. pandasのデータをグラフにする

2. 棒グラフで比較する

3. 折れ線グラフで変化を見る

4. グラフからデータの特徴を読み取る

**教材**

`03_matplotlib/lesson03_matplotlib.ipynb`

→ **[Google Colabで開く](https://colab.research.google.com/github/mhirayama/python-study-group/blob/main/03_matplotlib/lesson03_matplotlib.ipynb)**

---

### 第4回　Pythonで機械学習を体験してみよう

データを使って、コンピュータに学習させてみましょう。

第4回では、いよいよ機械学習を体験します。

機械学習とは何なのかを簡単に説明したあと、実際のデータを使ってモデルをつくり、予測してみます。

データを用意し、学習用と評価用に分け、モデルを学習させ、予測結果を確認します。

これまで学んできたPythonやデータ分析の知識を使いながら、機械学習の一連の流れを実際にコードを動かして体験します。

**主な内容**

1. 機械学習とは何かを知る

2. 学習用データと評価用データに分ける

3. データからモデルをつくる

4. モデルを使って予測する

5. 予測結果を確認する

**教材**

`04_machine_learning/lesson04_machine_learning.ipynb`

→ **[Google Colabで開く](https://colab.research.google.com/github/mhirayama/python-study-group/blob/main/04_machine_learning/lesson04_machine_learning.ipynb)**

---

# 事前準備

当日までに、次の準備をお願いします。

## 1. Googleアカウント

Google Colabを利用するため、Googleアカウントをご用意ください。

## 2. ノートパソコン

当日は、ご自身のノートパソコンを使用します。

## 3. Google Colab

教材はGoogle Colabを使用します。

各回の教材を開き、コードを実行できることを事前に確認してください。

---

# 使用する環境

- Python

- Google Colab

- pandas

- Matplotlib

- scikit-learn

基本的には、Google Colab上でコードを実行するため、Pythonの環境を自分で構築する必要はありません。

---

# 教材の使い方

各回の教材は、Google Colabで開いて使用します。

基本的には、上から順番にコードを実行してください。

コードを読むだけではなく、

**実際にコードを実行する → 結果を見る → 少し変更してみる**

という使い方をおすすめします。

分からないところがあっても、そのまま進めて構いません。

勉強会では、実際にコードを動かしながら一緒に確認していきます。

---

# 勉強会の進め方

この勉強会では、次の流れを大切にしています。

**説明する → コードを動かす → 結果を見る → 考えてみる**

最初からすべてを理解する必要はありません。

まずはPythonを実際に動かしてみて、少しずつ

**Python → データ → グラフ → 機械学習**

へと進んでいきます。

---

# 全4回を通した学習の流れ

```text
第1回
Pythonを動かしてみる
        ↓
第2回
pandasでデータを扱う
        ↓
第3回
Matplotlibでデータを見る
        ↓
第4回
機械学習でデータから予測する
```

Pythonの基本から始めて、データを扱い、グラフでデータを見て、最後に機械学習による予測まで体験します。

---

# リポジトリ構成

```text
python-study-group/
│
├── README.md
│
├── 01_python/
│   └── lesson01.ipynb
│
├── 02_pandas/
│   ├── lesson02_pandas.ipynb
│   └── sales.csv
│
├── 03_matplotlib/
│   └── lesson03_matplotlib.ipynb
│
└── 04_machine_learning/
    └── lesson04_machine_learning.ipynb
```

---

# 対象

- Pythonをこれから始めてみたい方

- データ分析に興味がある方

- 機械学習を体験してみたい方

- プログラミングを実際に動かしながら学びたい方

高校生以上を対象とし、年齢の上限は設けません。

プログラミング経験がなくても参加できます。

---

# おわりに

この勉強会では、難しい理論を最初から詳しく学ぶことよりも、**実際にPythonを動かして、データを扱い、その結果を自分で見てみること**を重視します。

小さく、ゆっくり、実際にやってみる。

そんなところから、Pythonとデータ分析を始めてみましょう。
