# ベースイメージとしてPython 3.11を使用
FROM python:3.11

# 作業ディレクトリを設定
WORKDIR /app

# 必要なパッケージをインストール
RUN pip install streamlit pandas tabulate

# アプリケーションのソースコードをコピー
COPY app.py .

# Streamlitアプリケーションを起動
CMD ["streamlit", "run", "app.py", "--server.port=8501"]
