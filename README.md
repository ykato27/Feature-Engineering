# Feature_Selection
* 変数選択全般のプログラム

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

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Feature_Selection）
```
cd Desktop/Feature_Selection
```

* Dockerによる環境構築（フォルダをマウント：Desktop/Feature_Selection）
```
docker-compose up --build
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている

## jupyter notebook説明
* Feature_Selection.ipynb : 変数選択のnotebook
