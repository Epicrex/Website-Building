# Forword
There are 2 ways of viewing html pages. The first and most simple way is simpe opening the .html file in the browser and making sure the .javascript files it needs are in the same directory. This approach is however only viable for very simple things, when reading/ writing from files in that diectory or using javascript libraries, one will need to use approch 2. So basically when things don't work with 1 then use 2.Approach 2 is buiding the .html file and everything it needs with npm.

The setup will be different depending on if you are using Vue or not.

# Basic HTML Setup
Right click the `index.html` file and click `Open with Live Server`. This will open a page in your browser.

# Vue Setup
## Prerequsites
- Install Node JS
- Inside of visual stuido code and install the "vue volar extension pack"

## Create Project
Run following commands in console of code editor:
```
npm install -g @vue/cli
```
```
npm init vue@latest
```
```
npm install
```
```
npm install vue-router@4
```
Then create following files:
- "views" folder in src
- "router.js" file in src

## Run server
For development use:
```
npm run dev
```
```
http://localhost:3000/
```
For production use:
```
npm run build
```
```
npm run preview
```
To close server use:
- Ctrl + C in console window

# Overview
### Views folder
- Pages

### Components folder
- Modules

### App.vue
- Router
- Modules that should allways be seen (Header navigation bar, footer, cookie accept)

### router.js
- For routing pages

### assets folder
- Images

# Documentation links
- https://vuejs.org/guide/quick-start.html


