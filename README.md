# H1 Git 

----

## H2 Основные комманды
* git status — показывает состояние рабочего каталога и индекса.
* git add <file> — добавляет файл в индекс.
* git commit -m "message" — создает коммит с сообщением.
* git push origin <branch> — отправляет изменения в указанную ветку удаленного репозитория.
* git pull — извлекает изменения из удаленного репозитория и сливает с локальной веткой.

----

## H2 Установка Git и создание SSH-ключа
###3 SSH-ключ 
Можно создать в любом месте, потом копируем публичный (id_rsa.pub) и добавляем его в настроках GitHub.
```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

###3 Клонирование репозитория или настройка существующего
```bash
cd /d/your_project_directory
git clone git@github.com:your_username/your_repository.git
cd your_repository
```

###3 Работа с репозиторием 
Важно! Не забывай делать коммиты, для этого 
```bash
git add .
git commit -m "Your commit message"
git push origin main
```
----

## H2 Ссылки
[Документация Git](https://git-scm.com/doc "Забавное название, говоря гит - волей не волей чувствуешь себя школьником, творящим мелкую пакость")
[Руководство GIt]( "https://docs.github.com/en")
