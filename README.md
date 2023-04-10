# _Template Repository_

#### By _**Gareth Grindeland**_

#### _A template showing the file structure for a new project._

## Technologies Used

* Git
* HTML
* CSS
* JavaScript
* Bootstrap version 5.2.3
* ESLint version 8.18.0
* Dillinger online markdown editor
* node version 16.13.1
* npm version 8.1.2

## Description

_This is an template for a basic project repository with instructions on how to install node webpackages, loaders, and plugins. Use this project as a walkthrough with to configure new webpacks or clone this repo and change file names and dependencies accordingly._
## File Structure
```
template-repo/
├── src/
│   ├── // Our source code goes in src/
│   ├── // The JS, CSS, and HTML files in here change from project to project
│   ├── index.js // We always need to include the entrypoint JS file called index.js
│   └── index.html // We always need to include a template HTML file called index.html
├── package.json  // In this file we need to update the "name" key to the name of the project
├── webpack.config.js
├── .gitignore
├── .eslintrc
└── README.md
```


## Setup/Installation Requirements

* _Clone this repository to your desktop._
* _If you are creating a new repository, make sure the first file you add and commit is the .gitignore file._
* _Navigate to the top level of the directory._
* _Update the "name" key in the package.json file to the name of the new project_
* _If there are other source files to add (CSS, JS, and HTML), make sure to import them to the index.js entry point file._
* _To generate a new package.json file, run this in the command line:_
```
$ npm init -y
```
* _Run the following code to install packages:_
```
$ npm install
<!if you run into errors, delete node_modules file and rerun the install command---->
$ npm run build     <!tell webpack to build the bundle---->
$ npm run start     <!build the project and serve it with a web server---->
```
* _After completing this setup, we're ready to write code in the src folder._



## Known Bugs

* _No known bugs_

## License

_MIT License_

_Copyright (c) 2023 Gareth Grindeland_

_Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:_

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
