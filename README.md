# ライブラリ

```
$ pipenv install wsgi-basic-auth
```

# Basic認証設定

```wsgi.py
...
application = BasicAuth(application)
...
```

# ユーザー名・パスワード設定

環境変数に追加

```.env
WSGI_AUTH_CREDENTIALS = [ユーザー名]:[パスワード]
```
