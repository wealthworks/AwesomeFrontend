# honcho

honcho 是一个 task runner，*Procfile* 是它的配置文件。

```
$ cat Procfile
web: python manage.py runserver
fe: npm start
```

- `honcho start` 会执行所有任务
- `honcho start web` 只启后端，在另一个 terminal 里启前端
- `honcho run python` 有时候需要进 python shell 做一些操作
