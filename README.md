# Feature-Engineering

- 特徴量エンジニアリング全般のプログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── .dockerignore        
├── Dockerfile                Dockerファイル
├── docker-compose.yml
└── notebook                  jupyter notebook
```

## 環境構築

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Feature-Selection）

```
cd Desktop/Feature-Selection
```

- Dockerによる環境構築（フォルダをマウント：Desktop/Feature_Selection）

```
docker-compose up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## jupyter notebook説明

- [Feature_Selection.ipynb](https://github.com/ykato27/Feature-Selection/blob/main/notebook/Feature_Selection.ipynb) : 変数選択のnotebook
- [Boruta_Feature_Selection.ipynb](https://github.com/ykato27/Feature-Selection/blob/main/notebook/Boruta_Feature_Selection.ipynb) : Borutaで変数選択のnotebook

## Display notebooks

- [View Jupyter notebooks in nbviewer](https://nbviewer.jupyter.org/github/ykato27/Feature-Engineering/tree/main/notebooks/)

## 動作環境

マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
