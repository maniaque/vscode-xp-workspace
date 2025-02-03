# XP Workspace [![Docker Pulls](https://img.shields.io/docker/pulls/aw350m3/vscode-xp-workspace?color=g&style=plastic)](https://hub.docker.com/r/aw350m3/vscode-xp-workspace) [![Latest Version](https://img.shields.io/docker/v/aw350m3/vscode-xp-workspace?color=g&style=plastic)](https://hub.docker.com/r/aw350m3/vscode-xp-workspace/tags?page=1&name=latest)


Данный проект помогает автоматизировать развёртывание рабочего окружения для написания правил на языке XP.

<p align="center">
  <img alt="XP Workspace in action" src="https://user-images.githubusercontent.com/61383585/236648422-aeb606f4-5e65-4914-b804-09b9cc97d399.png">
</p>

При создании рабочего окружения используются проекты:
- [code-server](https://coder.com/docs/code-server/latest/install)
- [open-xp-rules](https://github.com/Security-Experts-Community/open-xp-rules)
- [xp-kbt](https://github.com/vxcontrol/xp-kbt)

## Начало работы

### Требования
Для работы вам понадобится любой современный браузер и актуальная версия [Docker](https://www.docker.com/).

### Запуск
x. Скачайте репозиторий [vscode-xp-workspace](https://github.com/maniaque/vscode-xp-workspace).  
Например, через git: `git clone https://github.com/maniaque/vscode-xp-workspace.git`
x. В командной оболочке перейдите в папку `vscode-xp-workspace`
x. Выполните команду `docker-compose up -d`.
x. Откройте в браузере ссылку [http://localhost:3503/](http://localhost:3503/). Вас попросят ввести пароль.
x. Пароль: 12345
x. Окружение готово к работе, успехов в исследованиях! 