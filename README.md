- создаем папку: mkdir sprint-3_hw1-git
- перемещаемся туда: cd sprint-3_hw1-git
- инициализируем локальный репозиторий: git init
- создаем нужные файлы: touch README.md
- записываем в [README.md](http://README.md) инструкции: echo “какой-то текст” >> README.md
- добавляем в “отслеживаемые” файлы и сразу коммитим: git add . && git commit -m “Создаем [README.md](http://README.md) с инструкциями”
- отправляем проект на удалённый репозиторий: git push -u origin main

**Создаем удалённый публичный репозиторий:**

- Нажмите `+` рядом с иконкой профиля и выберите New repository
- в **Repository Name** — указываем название репозитория
- **Description** — описание проекта
- выбираем **Public** или **Private** — уровень доступа к репозиторию для других пользователей
- по инструкции на странице **“…or push an existing repository from the command line”**, с помощью SSH  - командами связываем локальный репозиторий с удалённым:
    - git remote add origin git@github.com:<имя_профиля>/<название_проекта>.git
    - git branch -M main
    - git push -u origin main
