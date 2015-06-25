# React-Restful

API Rest with React.js


### Documentation
- link "sample app with React.js + ES6" -> https://carlosazaustre.es/blog/ejemplo-de-aplicacion-con-react-js-en-ecmascript-6/
- link "API Rest + React.js + ES6" -> https://carlosazaustre.es/blog/consumiendo-un-api-rest-desde-react-js-con-ecmascript6/

### Directory Layout

```
.
├── /build/                     # The folder for compiled output
│   ├── /js/                    #
|   |   ├── bundle.js           #
|   ├── index.html              #
├── /node_modules/              # 3rd-party libraries and utilities
├── /src/                       # The source code of the application│
│   ├── /components/            # React components
|   |   ├── empleado-app        #
|   |   |   ├── index.jsx       #
|   |   |   ├── index.styl      #
|   |   ├── empleado-avatar     #
|   |   |   ├── index.jsx       #
|   |   |   ├── index.styl      #
|   |   ├── empleado-list       #
|   |   |   ├── index.jsx       #
|   |   |   ├── index.styl      #
|   |   ├── empleado-row        #
|   |   |   ├── index.jsx       #
|   |   |   ├── index.styl      #
│── gulpfile.js                 # Configuration file for automated builds
│── README.md                   # This
│── .gitignore                  #Ignore files in Git
```

### Getting Started

Just [clone](github-windows://openRepo/https://github.com/dMartinezAyuso/React-Restful.git) or
[fork](https://github.com/dMartinezAyuso/React-Restful.git/fork) the repo and start hacking:

```shell
$ git clone https://github.com/dMartinezAyuso/React-Restful.git MyApp
$ cd MyApp
$ npm install -g gulp           # Install Gulp task runner globally
$ npm install                   # Install Node.js components listed in ./package.json
```

### How to Build

```shell
$ gulp build
```

### How to Run

```shell
$ gulpfile
```
