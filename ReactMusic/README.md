# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

学习地址：https://www.bilibili.com/video/BV1x9rUYxEhL

Node版本：18.14

构建工具：Webpack

1.使用 create-react-app --template typescript 创建项目

2.项目配置

1.  配置项目图标：public->favicon.icon
2.  配置项目标题：public->index.html->title
3.  配置别名
    1.  使用 craco: create react app config
    2.  安装 craco：npm i @craco/craco@alpha -D
    3.  新建 craco.config.js 进行相关内容配置
    4.  修改 tsconfig.ts 中的相关配置：见代码提交记录
    5.  修改 package.json 中的相关配置：见代码提交记录
4.  配置prettier：npm i prettier - D
    1.  新建相关文件进行补充修改
    2.  package.json中新增 "prettier": "prettier --write ." 指令
    3.  配置 ignore 文件进行代码全部格式化
5.  配置eslint：npm i eslint - D
    1.  npx eslint --init
        1.  problems
        2.  esm
        3.  react
        4.  typescript
        5.  brower
    2.  npm i eslint-plugin-prettier eslint-config-prettier -D
