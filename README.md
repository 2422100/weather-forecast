# weather-forecast

気象庁（JMA）の天気予報データを取得・表示するアプリケーション。

## セットアップ

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## 実行

```bash
python -m jma_weather.main
```

## ディレクトリ構成

```
weather-forecast/
├── data/                # 地域データ
├── src/jma_weather/     # アプリケーション本体
│   └── ui/              # UIコンポーネント
└── tests/               # テスト
```
