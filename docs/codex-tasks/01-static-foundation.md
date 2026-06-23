# Codex Task 01 v2 — Static foundation

## Статус

Задача не запускается до статуса `SOURCE INTEGRITY PASSED` в `docs/source-integrity-report.md`.

## Цель

Создать полностью читаемую статическую версию утверждённой семиэкранной страницы. На этом этапе не реализовывать sticky-механику, `IntersectionObserver` или другие интерактивы.

## Repository and base branch

- repository: `can-did/unforgettable-bag-interactive-case`
- base branch: `main`
- работа только в новой отдельной ветке
- результат: новый pull request в `main`

## Read first

1. `AGENTS.md`
2. `docs/project-brief.md`
3. `docs/storyboard.md`
4. `docs/content.md`
5. `docs/visual-spec.md`
6. `docs/source-integrity-report.md`

## Files allowed to change

- `index.html`
- `styles.css`

## Files forbidden to change

- `README.md`
- `AGENTS.md`
- `docs/**`
- `assets/**`
- `.nojekyll`
- `.gitignore`

## Required implementation

- семь разделов в утверждённом порядке;
- утверждённые заголовки и тексты без переписывания;
- семь открытых статичных шагов механики;
- четыре подтверждённые метрики;
- две фразы интерпретации непосредственно под метриками;
- три реальных ограничения пилота;
- точное разделение роли автора и команд;
- ссылки на Notion и возврат к механике;
- реальные изображения по существующим относительным путям;
- семантическая структура и полная читаемость без JavaScript.

## Technical constraints

- без JavaScript;
- не создавать `script.js`;
- без framework, npm, bundler и внешних зависимостей;
- только относительные пути;
- GitHub Pages project-site safe;
- не добавлять sticky navigation без отдельного требования;
- не использовать broken paths или placeholders.

## Stop conditions

Остановить задачу и не менять HTML/CSS, если:

- `SOURCE INTEGRITY PASSED` отсутствует;
- обязательный source-файл отсутствует или сокращён;
- обязательный asset отсутствует;
- задача противоречит AGENTS.md или docs/;
- указан неверный repository или base branch.

## Acceptance criteria

1. Изменены только `index.html` и `styles.css`.
2. Все семь разделов и семь шагов присутствуют.
3. Тексты дословно соответствуют `docs/content.md`.
4. Реальные изображения загружаются без 404.
5. Нет JavaScript и внешних зависимостей.
6. Desktop соответствует 1240 px grid и 2×2 metrics.
7. Mobile работает на 320, 375 и 430 px без горизонтального scroll.
8. Проверены 768, 1280 и 1440 px.
9. Keyboard navigation и focus работают.
10. Основной смысл доступен без взаимодействия.
11. Task 02 не начат.

## Required report

- changed files;
- used assets;
- test results for 320, 375, 430, 768, 1280 and 1440 px;
- keyboard and focus result;
- console and 404 result;
- remaining deviations;
- confirmation that Task 02 was not started.
