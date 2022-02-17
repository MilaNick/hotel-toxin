# ✨ Metalamp task 2 v.1 ✨
Проект реализуется в рамках образовательной программы [Metalamp](https://www.metalamp.ru/education)  
[Переход на страницу](https://milanick.github.io/hotel-toxin/)  
<hr>

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
$ rm -rf dist
$ echo  " dist/ "  >> .gitignore
$ git worktree add dist gh-pages
$ cd dist
$ git add --all
$ git commit -m " Deploy to gh-pages "
$ git push origin gh-pages

```
