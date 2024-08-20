[На главную](./readme.md) 

[<назад ](./git%20init.md)  \  [ далее >](./add.md)

### git status

Эта команда используется для проверки текущего состояния репозитория.

```bash
git status
```

Вы увидите:

```bash
git status
On branch main
nothing to commit, working tree clean
```
Если после выполнения предыдущей команды вы видите `On branch master` вместо `On branch main`, это означает, что у вас немного устаревшая версия **Git**, которая не поняла нас, когда мы попросили установить имя ветки по умолчанию на main. В этом случае вы можете переименовать ветку в main с помощью следующей команды:

```bash
git branch -m master main
```
