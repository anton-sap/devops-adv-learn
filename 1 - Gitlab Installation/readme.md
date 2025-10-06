## Установка Gitlab CE

Установку будем производить на облачный сервер на базе Ubuntu 24.04

Добавляем репозиторий в систему:

`curl "https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.deb.sh" | sudo bash`

Объявляем переменную и ставим пакет:

`sudo EXTERNAL_URL="https://gitlab.saprykin.uz" apt install gitlab-ce`