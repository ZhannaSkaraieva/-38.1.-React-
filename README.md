# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


# -38.1.-React-

Мета: Створення базового React проєкту з компонентом кнопки та / або текстового поля.

Постановка задачі:

Ініціалізація проєкту:Використовуючи npx або yarn, створіть новий React проєкт:

З create-react-app: npx create-react-app ваш*проект або yarn create react-app ваш*проект.
З Vite: npm create vite@latest ваш*проект -- --template react або yarn create vite ваш*проект --template react.
Перейдіть до каталогу проєкту (cd ваш_проект) та встановіть залежності (npm install або yarn).
Створення компоненту:

У src/components створіть файл Button.jsx або Input.jsx.
Реалізуйте компонент, який приймає і використовує props (text і onClick для кнопки, placeholder і onChange для поля введення).
Використання компоненту:

Імпортуйте та використовуйте ваш компонент у App.js (або App.jsx), передаючи необхідні props.
Тестування проєкту:

Запустіть проєкт (npm run dev або yarn dev для Vite, npm start або yarn start для create-react-app) та перевірте роботу компонента.
Вимоги до здачі:

Репозиторій на GitHub з вашим проєктом.
Всі важливі зміни мають бути видно у історії комітів.
README.md з інструкціями по запуску проєкту.

1.проверка подключения npx
npx --v

2. npx create-react-app .  (. ставиться если создается проект в сущ.директории. также в названии диреткории, куда устанавливаем проэкт не должно быть заглавных букв)

3.обновляем  приложение с помощью утилиты Create React App
npm i create-react-app 

4.изменяем версию react в package.json, package-lock.json

5.инициализируем проэкт 
npm install

6.исправляем ошибки, путем ручной доустановки компонентов  
npm i web-vitals

7.проверка работоспособности проэста
npm run build
# -38.1.-React-

Мета: Створення базового React проєкту з компонентом кнопки та / або текстового поля.

Постановка задачі:

Ініціалізація проєкту:Використовуючи npx або yarn, створіть новий React проєкт:

З create-react-app: npx create-react-app ваш*проект або yarn create react-app ваш*проект.
З Vite: npm create vite@latest ваш*проект -- --template react або yarn create vite ваш*проект --template react.
Перейдіть до каталогу проєкту (cd ваш_проект) та встановіть залежності (npm install або yarn).
Створення компоненту:

У src/components створіть файл Button.jsx або Input.jsx.
Реалізуйте компонент, який приймає і використовує props (text і onClick для кнопки, placeholder і onChange для поля введення).
Використання компоненту:

Імпортуйте та використовуйте ваш компонент у App.js (або App.jsx), передаючи необхідні props.
Тестування проєкту:

Запустіть проєкт (npm run dev або yarn dev для Vite, npm start або yarn start для create-react-app) та перевірте роботу компонента.
Вимоги до здачі:

Репозиторій на GitHub з вашим проєктом.
Всі важливі зміни мають бути видно у історії комітів.
README.md з інструкціями по запуску проєкту.

1.проверка подключения npx
npx --v

2. npx create-react-app .  (. ставиться если создается проект в сущ.директории. также в названии диреткории, куда устанавливаем проэкт не должно быть заглавных букв)

3.обновляем  приложение с помощью утилиты Create React App
npm i create-react-app 

4.изменяем версию react в package.json, package-lock.json

5.инициализируем проэкт 
npm install

6.исправляем ошибки, путем ручной доустановки компонентов  
npm i web-vitals

7.проверка работоспособности проэста
npm run build

8.создание папки src/components 
  mkdir src/components

  
9.запуск 
npm run start