# Shoes Villains

2D-игра на движке **Godot 4**, объединяющая ключевые идеи **Helmet Heroes** и **Dead Cells**.

## Центр управления (GitHub)

GitHub используется как единый центр управления разработкой:

- **Kanban-доска:** [Shoes Villains Board](https://github.com/users/vladospopires-source/projects/1) (`Backlog` → `Ready` → `In progress` → `In review` → `Done`)
- **План и этапы:** [Milestones](../../milestones) (`M0: Foundation & Architecture`, `M1: Core Loop Prototype`, `M2: Vertical Slice`)
- **Задачи и баги:** [Issues](../../issues) с шаблонами и метками (`area:*`, `type:*`, `priority:*`)
- **Версии игры:** [Releases](../../releases) с тегами формата `vX.Y.Z`
- **Изменения:** ветки от `main` + Pull Requests с привязкой к Issue (`Closes #...`)

## Структура репозитория

Проект организован как клиент-серверный монорепозиторий. Правила взаимодействия слоёв описаны в [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md).

- `.github/` — шаблоны Issue и Pull Request
- `docs/` — игровая документация, GDD, архитектура и протоколы
- `client/` — клиент игры на Godot 4
- `server/` — серверная часть игры
- `shared/` — общие контракты, схемы сообщений и таблицы баланса
- `art_src/` — рабочие исходники графики и аудио (вне проекта Godot)
- `tools/` — вспомогательные скрипты и утилиты пайплайна
