buildpackの設定をしないとnodejsとみなされてしまうのが落とし穴だった
herokuでの設定の方法は以下
```$ heroku buildpacks:set heroku/python
