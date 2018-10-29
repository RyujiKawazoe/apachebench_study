負荷ツール
---

* apache bench
    * docker imageを利用 https://hub.docker.com/r/jordi/ab/


How to Start
---

```
docker-compose run apachebench
```


Apache Benchメモ
---

```
ab -e $FILE -n 10 -c 1 -t 15 $URL

# -e csvで出力する
# -n 総リクエスト
# -c コネクション数
# -t タイムアウト
```
