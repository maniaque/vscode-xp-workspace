# XP Workspace 

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
1. Скачайте репозиторий [vscode-xp-workspace](https://github.com/maniaque/vscode-xp-workspace).  
Например, через git: `git clone https://github.com/maniaque/vscode-xp-workspace.git`
2. В командной оболочке перейдите в папку `vscode-xp-workspace`
3. Выполните команду `docker-compose up -d`.
4. Откройте в браузере ссылку [http://localhost:3503/](http://localhost:3503/). Вас попросят ввести пароль.
5. Пароль: 12345
6. Окружение готово к работе, успехов в исследованиях! 