# База по Git 

----

## Основные комманды
* git status — показывает состояние рабочего каталога и индекса.
* git add <file> — добавляет файл в индекс.
* git commit -m "message" — создает коммит с сообщением.
* git push origin <branch> — отправляет изменения в указанную ветку удаленного репозитория.
* git pull — извлекает изменения из удаленного репозитория и сливает с локальной веткой.

----

## Установка Git и создание SSH-ключа
### SSH-ключ  
Можно создать в любом месте, потом копируем публичный (id_rsa.pub) и добавляем его в настроках GitHub.
```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

### Клонирование репозитория или настройка существующего
```bash
cd /d/your_project_directory
git clone git@github.com:your_username/your_repository.git
cd your_repository
```

### Работа с репозиторием 
Важно! Не забывай делать коммиты, для этого 
```bash
git add .
git commit -m "Your commit message"
git push origin main
```
----

## Ссылки
[Документация Git](https://git-scm.com/doc "Забавное название, говоря гит - волей не волей чувствуешь себя школьником, творящим мелкую пакость")  
[Руководство Git]( https://docs.github.com/en)  
[Markdown](https://gist.github.com/fomvasss/8dd8cd7f88c67a4e3727f9d39224a84c"Очень крутая шпаргалка на русском")
