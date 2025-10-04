# Developer Experience Starter Kit

Этот пакет — готовый каркас DX: спецификация OpenAPI, шаблон SDK на TypeScript и примеры.
Задача: чтобы новый разработчик получил **первый успешный вызов API за < 5 минут**.

## Состав

- `openapi.yaml` — спецификация OpenAPI 3.0.3 (стартовая, примерная)
- `sdk-js/` — минимальный SDK на TypeScript
- `postman-collection.json` — коллекция для Postman/Insomnia
- `docs/` — HTML для отображения документации (Redoc)

### Быстрый старт (локально, опционально)
```bash
cd sdk-js
npm install
npm run build
node dist/examples/balance.js
## update
