# 2023年秋学期 産業地理学 中間&期末レポート
Created by 2120274m

このリポジトリは2023年秋学期産業地理学の中間レポート及び期末レポートを再現するためのコードを格納したリポジトリです。

## ディレクトリ構成
本リポジトリは次のような構成を取っています：
- `notebooks`
    - `mid/mid_main.ipynb`: 中間レポートの分析を行っているノートブックです
    - `final/final_main.ipynb`: 期末レポートの分析を行っているノートブックです
- `reports`
    - `notebooks`の成果物が格納されています
    - `mid`と`final`に分かれています
    - 今回は提出したFigureや`.csv`が格納されています
        - 実際に提出したファイルはこれらのファイルを名前変更だけ行ったものです
- （`data`）:
    - 前処理されたデータが格納されています
    - 二次配布を防ぐためフォルダごと`git ignore`されています


## 再現方法
1. `git clone`
2. `pip install -r requirements.txt`
3. `mid/mid_main.ipynb`または`final/final_main.`を上から順に実行