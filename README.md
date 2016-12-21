#100 things to know about yeoman
## Here are the commands you should know about the website generator Yeoman courtesy of [https://www.youtube.com/watch?v=gKiaLSJW5xI](https://www.youtube.com/watch?v=gKiaLSJW5xI)


### Yeoman is a workflow tool that consists of three different tools - Yo (scaffolding tool for creating reusable projects), Gulp (task runner for automating tasks) and Bower (package dependency manager)

1. npm install -g yo
2. npm install -g generator-webapp
3. yo doctor (tells you if everything is setup correctly)
4. yo webapp
  (running yo webapp creates the following files and folders)
    folders
      - App (!!always work in the app folder)
      - Bower_components
      - Node_modules
      - test (Jasmine, Chai, Mocha unit tests)
    files
      - bower.json
      - gulp.js
      - package.json
    hidden files
      - .babelrc
      - .editorconfig
      - .gitignore
      - .bowerrc
      - .gitattributes
      - .yo-rc.json
5. (back in the terminal we should run) gulp
6. A new dist folder will be created
