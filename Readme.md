
npx --ignore-existing react-native init Getbeerapp --template react-native-template-typescript

eact-native start --reset-cache

react-native run-android

Delete eslint e prettier originais

criar /src/App.tsx

yarn add eslint -D
yarn eslint --init
espaço na opção Browser para não escolher nenhum
syleguide AirBnB
format - JSON
? Would you like to install them now with npm? Não
yarn add -D eslint-plugin-react@^7.19.0 @typescript-eslint/eslint-plugin@latest eslint-config-airbnb@latest eslint-plugin-import@^2.20.1 eslint-plugin-jsx-a11y@^6.2.3 eslint-plugin-react-hooks@^2.5.0 @typescript-eslint/parser@latest

yarn add prettier eslint-config-prettier eslint-plugin-prettier -D
yarn add eslint-import-resolver-typescript -D


## status bar
componente import { StatusBar } from react-native em App.tsx
