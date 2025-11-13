# Django Tutorial Project

## 概要

このプロジェクトは、**Django公式チュートリアル**に基づいて作成されたWebアプリケーションです。Djangoの基本的な機能（モデル、ビュー、テンプレート、管理画面など）を学習することを目的としています。

***

## 必要条件

*   Python 3.x
*   Django (公式チュートリアル推奨バージョン)
*   pip (Pythonパッケージ管理ツール)

***

## セットアップ手順

1.  **リポジトリをクローン**
    ```bash
    git clone https://github.com/ai208/djangotutorial.git
    cd djangotutorial
    ```

2.  **仮想環境を作成**
    ```bash
    python -m venv venv
    source venv/bin/activate   # macOS/Linux
    venv\Scripts\activate      # Windows
    ```

3.  **依存パッケージをインストール**
    ```bash
    pip install -r requirements.txt
    ```

4.  **データベースを初期化**
    ```bash
    python manage.py migrate
    ```

5.  **開発サーバーを起動**
    ```bash
    python manage.py runserver
    ```

***

