### Тестовый репозиторий

## Как использовать Git в связке с GitHub

### Авторизация

```bash
git config --global user.name 'Ваше имя'
git config --global user.email адрес-почты-без-кавычек
git config --list
```

Чтобы выйти из режима просмотра, нажмите `Q`

### Создание репозитория

```bash
git init
git status
git add .
git commit -am “Init commit”
```

### Подключение ремоута

```bash
	git remote add origin *ссылка-с-гитхаба*
```
