# ベースイメージとしてPython 3.8を使用
FROM python:3.9

# 作業ディレクトリを設定
WORKDIR /src

# 必要なPythonパッケージをインストール
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# プロジェクトのファイルをコピー
COPY . .

