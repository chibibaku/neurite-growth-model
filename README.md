# neurite-growth-model

神経突起（neurite）の成長モデルを、Jupyter Notebook (Python環境)で確認するためのリポジトリです。
このリポジトリの内容は、以下の記事を出典・参考元として作成しています。

- 出典: [神経突起の成長モデル — Juliaで学ぶ計算論的神経科学](https://compneuro-julia.github.io/neuron-model/neurite-growth-model.html)

## 内容

- `neurite-growth-model_py.ipynb`: Pythonで動作を確認するための移植版ノートブック

主な題材は、神経突起を木構造として扱い、分岐・伸長・転向を含むVan Peltモデルに基づいて成長過程をシミュレーションするものです。

## Python環境

実行にはuv環境を推奨します。以下のコマンドで環境を構築できます。
`uv sync`で`pyproject.toml`を読み込んで依存関係をインストールしてください。

- numpy
- matplotlib
- tqdm
- ipywidgets
- ipykernel

## 注記

学習・確認用の実装です。理論的な説明や元のJulia実装については、上記の出典記事を参照してください。
