yarn global add babel-cli
npm install -g babel-cli

yarn init
yarn add babel-preset-env babel-preset-react

babel src/app.js --out-file public/script/app.js --presets=env,react
babel src/app.js --out-file public/script/app.js --presets=env,react --watch

--styling scss
yarn add css-loader style-loader
yarn add sass-loader node-sass