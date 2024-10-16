## Локальный запуск сайта (Первичная настройка)

1) `brew install pipx`
2) `pipx ensurepath`
3) `pipx install mkdocs`
4) Необходимо перейти в директорию проекта в терминале
5) `python3 -m venv venv source venv/bin/activate`
6) `pipx runpip mkdocs install mkdocs-roamlinks-plugin mkdocs-rss-plugin pymdown-extensions`
7) `mkdocs serve`

#### Если все пакеты уже установлены
1) `mkdocs serve`
