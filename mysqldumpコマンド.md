参照 : https://dev.mysql.com/doc/refman/8.0/ja/mysqldump.html

『MySQL』のバックアップ及びデータの復元には、```mysqldump```コマンドを利用

```mysqldump```はMySQLをインストールすると使用できるコマンド。

- バックアップ方法

```
 mysqldump -h ホスト名 -u ユーザ名 -pパスワード [オプション] > dump.sql
```

- 復元方法
```
mysql -h ホスト名 -u ユーザ名 -pパスワード < dump.sql
```

***★***```mysqldump```と```mysql```,「>」不等号の向きが異なる
