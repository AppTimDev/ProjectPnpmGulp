# Pnpm and Gulp4
Objectives: Aims to use the latest verision of gulp and nodejs in new project so that it is easier to 
work with web front-end project. It increases the speed in development and optimizes the project to maximize the site speed and performance.

- Upgrade my old project using gulp 3.8, npm and old veriosn of node
https://github.com/AppTimDev/ProjectGulp
- Upgrade gulp 3.8 to gulp 4
- Replace npm with pnpm

---

Use gulp.js 4 as a task runner
- Clean all files in destination folder
- Compress the file size of images
- Copy files to destination folder
- Minify html
- Minify css
- Minify and uglify js 
- Combine all files to a bundle file
- Create a webserver with liveload
- Watch file changes in development and production mode and auto hot reload to see the browser changes
- Deploy the project automatically to github

---

## Environment:
- Windows 10
- nvm 1.1.11
- node v20.1.0
- npm 9.6.4
- pnpm@8.5.0

---

## Project setup
### Installation
### `Nvm`
Install nvm using choco
```sh
choco install nvm
```

### `Node`
Install node js (latest or the version used here) using nvm
```sh
nvm install latest
nvm install 20.1.0
```
and starting  using node js (latest or the version used here)
```sh
nvm use latest
nvm use 20.1.0
```

### `pnpm`
Install pnpm (latest or the version used here) using npm
```sh
npm install -g pnpm
npm install -g pnpm@8.5.0
```

### Install all the node packages in package.json
```sh
pnpm i
```

### Run the project
It runs the default task of gulp
```sh
pnpm gulp
```

---

### Gulp4
Note: In my project, Gulp is only installed locally now, to run the task, simply use pnpm command to start the task
- run the default task
```sh
pnpm gulp
```
- run the copy task
```sh
pnpm copy
```

---

## Version
### Check the version for nvm, node js and npm
```sh
nvm version
node -v
npm -v
```
1.1.11  
v20.1.0  
9.6.4  

### Check the version for gulp (after installation)
```sh
pnpm gulp -v
gulp -v
```
CLI version: 2.3.0  
Local version: 4.0.2

---

Commands used:
```sh
pnpm init
pnpm list
pnpm i --save-dev gulp
pnpm i --save-dev browser-sync rimraf gulp-concat gulp-rename
pnpm i --save-dev gulp-html-replace gulp-minify-html 
pnpm i --save-dev gulp-clean-css 
pnpm i --save-dev gulp-uglify gulp-terser
pnpm i --save-dev gulp-babel @babel/core @babel/preset-env 
pnpm i --save-dev gulp-webserver
pnpm i --save-dev gulp-imagemin@7.1.0
```

Note: 
- gulp-minify-css (deprecated)
- gulp-contrib-copy (not install)