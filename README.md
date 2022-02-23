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

- step 1  
Delete the dist directory from .gitignore of the project file
-  step 2
```
git add dist && git commit -m "  init dist "
```
- step 3  
Use the subtree push to send it to the gh-pages branch on GitHub.
```
git subtree push --prefix dist origin gh-pages
```

## Delete worktree
```
$ git worktree prune
git branch -D gh-pages
git push origin --delete gh-pages
```


