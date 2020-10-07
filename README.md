# parcel-deploy-tutorial

## Мастерская: деплой билда от Parcel на GitHub Pages

1. Редактрируем в package.json поле `"homepage": "https://ваше_имя.github.io/репозиторий"`
2. Устанавливаем пакет [`npm install gh-pages`](https://www.npmjs.com/package/gh-pages)
3. Добавляем npm-скрипты
   1. `"deploy": "gh-pages -d dist"`
   2. `"predeploy": "npm run build"`
