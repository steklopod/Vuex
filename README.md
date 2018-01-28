Данный проект потробно знакомит с **Vuex** - компонентой фрэймворка Vue js. 
Vuex используется как **единое хранилище данных** в приложении.
Основные понятия:
1. store;
2. getters;
3. nutations;
4. actions;
5. types;
6. modules;


## Установка (1 раз):

``` bash
npm install
```
## Запуск (каждый раз) на localhost:8080
```
npm run dev
```
#### production:
```
npm run build
```

#### Чтобы убить процесс на порту 8080 (Windows):
```
1. netstat -ano | findstr 8080
2. taskkill /pid @НОМЕР_ПОРТА@ /F
``` 
> Доп. зависимость:
``` 
 npm install --save-dev babel-preset-stage-2
``` 
