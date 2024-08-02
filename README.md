

# Django Blog

このプロジェクトは、Djangoフレームワークを使用して構築されたシンプルなブログアプリケーションです。ユーザーが投稿を作成、編集、削除できる基本的な機能を提供します。

## 機能

- **ユーザー認証**: ユーザーはアカウントを作成し、ログインして投稿を管理できます。
- **投稿管理**: 投稿の作成、編集、削除が可能です。
- **コメント機能**: 各投稿にコメントを追加できます。
- **カテゴリー**: 投稿をカテゴリーで分類する機能があります。

## インストールとセットアップ

1. **リポジトリをクローン**:

   ```bash
   git clone https://github.com/0xItoHub/Django_blog.git
   cd Django_blog
   ```

2. **仮想環境の作成**:

   ```bash
   python -m venv env
   source env/bin/activate  # Windowsの場合: env\Scripts\activate
   ```

3. **依存関係のインストール**:

   ```bash
   pip install -r requirements.txt
   ```

4. **データベースのマイグレーション**:

   ```bash
   python manage.py migrate
   ```

5. **スーパーユーザーの作成**:

   ```bash
   python manage.py createsuperuser
   ```

6. **サーバーの起動**:

   ```bash
   python manage.py runserver
   ```

   ブラウザで`http://127.0.0.1:8000/`にアクセスしてアプリケーションを確認できます。

## 使用技術

- **Django**: PythonのWebフレームワーク
- **SQLite**: デフォルトのデータベースエンジン
- **Bootstrap**: フロントエンドのスタイルとデザイン


## ライセンス

このプロジェクトはMITライセンスの下でライセンスされています。詳細は[LICENSE](LICENSE)ファイルを参照してください。

## コントリビューション

コントリビューションは大歓迎です。プルリクエストを提出する前に、[CONTRIBUTING](CONTRIBUTING.md)ガイドラインをお読みください。

