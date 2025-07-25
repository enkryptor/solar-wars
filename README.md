# Solar Wars

Многопользовательская пошаговая игра про дипломатию и перестрелки в космосе.


## Содержание

1. [О проекте](#о-проекте)  
2. [Установка](#установка)  
3. [Запуск](#запуск)  
4. [Тестирование](#тестирование) 
5. [Документация](#документация) 
6. [Лицензия](#лицензия)


## О проекте

За основу взята командная салонная игра, в которой сервер исполняет роль ведущего.


## Установка

```sh
git clone https://github.com/enkryptor/solar-wars.git
cd solar-wars
npm install
```


## Запуск

```sh
npx nx serve solar-wars-server
```

```sh
npx nx serve solar-wars-client-web
```


## Тестирование

Прогон модульных тестов:

```sh
npx nx test solar-wars-server
```

```sh
npx nx test solar-wars-client-web
```

Подсчёт покрытия:

```sh
npm run server:coverage
```

```sh
npm run client:coverage
```


## Документация

- Инструкция по внесению изменений: [CONTRIBUTE.md](CONTRIBUTE.md)
- Документация по API: http://localhost:3000/swagger/


## Лицензия

См. [MIT](LICENSE)
