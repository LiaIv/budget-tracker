# Budget Tracker CLI

Консольное приложение на TypeScript для учёта личных финансов

## Что будет уметь

- добавлять доходы и расходы с суммой, категорией и датой
- показывать список операций и текущий баланс
- считать итоги по категориям и за период

## Запуск

Нужен Node.js 18+

```bash
npm install
npm run build   # компиляция src/ → dist/
npm start       # запуск dist/index.js
npm run dev     # пересборка при изменениях
```

## Структура

```
budget-tracker-cli/
├── src/index.ts    # точка входа
├── dist/           # скомпилированный JS (не в git)
├── package.json
└── tsconfig.json
```
