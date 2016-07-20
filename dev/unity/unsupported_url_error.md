# UnityでWWWを利用してあるIPアドレスにアクセスしようとした時

```
unsupported URL
```

的なエラー文章が出たら

指定のIPアドレスが

```
192.xxx.x.x:hoge
```

となっていないか確認してみてください。

このような形式になっている場合、頭にhttp://をつければ解決する可能性があります。

つまり

```
http://192.xxx.x.x:hoge
```

に変更すれば治る可能性があります

AST問題とかはまた別の話（https://）にした方がいいかもしれん