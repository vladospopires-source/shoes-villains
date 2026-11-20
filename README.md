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

Архитектура папок будет расширяться по мере проектирования:

- `.github/` — шаблоны Issue и Pull Request
- `docs/` — *(планируется)* игровая документация, GDD, архитектура
- `client/` — *(планируется)* клиент игры на Godot 4
