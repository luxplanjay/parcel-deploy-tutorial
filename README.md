# parcel-deploy-tutorial

## Мастерская: деплой билда от Parcel на GitHub Pages

1. Редактируем скрипт build и добавляем `--public-url /имя_репозитория/`
2. Редактрируем в package.json поле `"homepage": "https://ваше_имя.github.io/имя_репозитория"`
3. Устанавливаем пакет [`npm install gh-pages`](https://www.npmjs.com/package/gh-pages)
4. Добавляем npm-скрипты
   1. `"deploy": "gh-pages -d dist"`
   2. `"predeploy": "npm run build"`
