
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

## styled-components
import styled from 'styled-components/native';
yarn add @types/styled-components -D

##Routes com React navigation
yarn add @react-navigation/native

instalçao seguindo a doc
https://reactnavigation.org/

yarn add react-native-reanimated react-native-gesture-handler react-native-screens react-native-safe-area-context @react-native-community/masked-view

navigation stack -
É navegação em pilhas, via botões, abas, drawer ect
em https://reactnavigation.org/docs/hello-react-navigation/
yarn add @react-navigation/stack


import 'react-native-gesture-handler'; no primeiro arquivo da aplicação -> App.tsx

executar run-android novamente

import navigationContainer from @react-navigation/native - precisa ficar por volta de toda a aplicação
Ele cria um Header automaticamente


