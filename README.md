# ✨ Metalamp task 2 v.1 ✨
Проект реализуется в рамках образовательной программы [Metalamp](https://www.metalamp.ru/education)  
<hr>

[Переход на страницу проекта](https://milanick.github.io/hotel-toxin/)  
Used [basic configuration of Webpack 5](https://github.com/MilaNick/webpack-template)  
The project uses Sass(Scss), Pug, Bootstrap, Jquery, React, Typescript

## 🚀 Quick start
- Clone this repo and npm install
```
npm i
```
Commands in terminal:  
- Development server
```
npm start
```
- Production build
```
npm run build
```
- Development mode
```
npm run dev
```

## To load a page on github pages  
the following commands are used:

```
$ cd dist
$ echo  " dist/ "  >> .gitignore
$ git add --all
$ git commit -m " Deploy to gh-pages "
$ git push origin gh-pages
$ git worktree add dist gh-pages
$ rm -rf dist
```
