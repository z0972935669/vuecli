# app

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

# 安裝
Node版本要求: 使用nvm, 推薦更高版本

### 使用以下指令進行安裝
```
npm install -g @vue/cli
#or
yarn global add @vue/cli
```

安裝完後，可以在命令行中訪問vue版本，驗證是否安裝完成。
----------------------------------------
vue --version
#or
vue -V

創建一個項目
========================================
vue create [project Name]

Vue CLI v4.5.11
? Please pick a preset: (Use arrow keys)
> Default ([Vue 2] babel, eslint)
  Default (Vue 3 Preview) ([Vue 3] babel, eslint) 
  Manually select features

● Default: 基本的 Babel + ESLint 預設選項
● Manually select features: 自己手動選擇

選取要安裝的部份
----------------------------------------
Vue CLI v4.5.11
? Please pick a preset: Manually select features
? Check the features needed for your project: 
 (*) Choose Vue version
 (*) Babel
 ( ) TypeScript
 ( ) Progressive Web App (PWA) Support        
 (*) Router
 (*) Vuex
>(*) CSS Pre-processors
 (*) Linter / Formatter
 ( ) Unit Testing
 ( ) E2E Testing

● Babel : JavaScript 編譯器、轉譯器。
● TypeScript : TypeScript 用來補足 JavaScript 在型別上的不足，
  添加了可選的靜態型別和使用看起來像類別基礎的物件導向編程語法操作 Prototype
● Progressive Web App (PWA) Support : 是否支援漸進式網頁應用 (PWA)
● Router : Vue 的路由器
● Vuex vuex（vue的狀態管理模式）
● CSS Pre-processors : CSS 前處理器（如：less、sass）
● Linter / Formatter : 程式碼風格檢查和格式化（如：ESlint）
● Unit Testing : 單元測試（unit tests）\
● E2E Testing : e2e（end to end） 測試

選擇用來啟動項目的Vue.js版本
----------------------------------------
Vue CLI v4.5.11
? Please pick a preset: Manually select features
? Check the features needed for your project: Choose Vue version, Babel, Router, Vuex, CSS Pre-processors, Linter
? Choose a version of Vue.js that you want to start the project with (Use arrow keys)
> 2.x
  3.x (Preview)

是否使用Router歷史記錄模式
----------------------------------------
? Use history mode for router? (Requires proper server setup for index fallback in production) (Y/n) y

預處理器
----------------------------------------
? Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by default): (Use arrow keys)
  Sass/SCSS (with dart-sass)
> Sass/SCSS (with node-sass)
  Less
  Stylus

● Sass/SCSS (with dart-sass): Sass 團隊改寫
● Sass/SCSS (with node-sass): 原先使用的

ESLint 協助讓你寫的程式符合規範的輔助工具，區分嚴謹程度
---------------------------------------
? Pick a linter / formatter config: 
  ESLint with error prevention only 
  ESLint + Airbnb config
> ESLint + Standard config
  ESLint + Prettier

代碼檢查時機
---------------------------------------
 ? Pick additional lint features: (Press <space> to select, <a> to toggle all, <i> to invert selection)
>(*) Lint on save
 ( ) Lint and fix on commit

● Lint on save: 存檔時
● Lint and fix on commit: 提交更新時

在哪為特性進行配置
---------------------------------------
? Where do you prefer placing config for Babel, ESLint, etc.? (Use arrow keys)
> In dedicated config files
  In package.json

● In dedicated config files: 在專用配置文件中
● In package.json: 在package.json

保存為未來項目預設
---------------------------------------
? Save this as a preset for future projects? (y/N)y

專案建置成功
---------------------------------------
Successfully created project ap
Get started with the following commands:

運行專案項目
---------------------------------------
cd [projectName]
npm run serve
