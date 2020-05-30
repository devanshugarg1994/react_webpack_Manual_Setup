# react_webpack_Manual_Setup
Setup of react app without using "create-react-app"

Open Project directory and type:-
### `npm install`

This command will download all the dependacy in the project. After that just start the server using following command.

In the project directory, you can run:

### `npm run start`

Runs the app in the development mode.<br>
Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

## Description

In the setup fo React we haven't used create-react-app cmd but instaed install react and react-dom manually.</br>

Setup contain "react" aand "react-dom" as dependencies.</br>

Setup use webpack to bundle the file and webpack-dev-server to use run server at [http://localhost:8080]</br>

We have use babel to transpile the ES6 code and react JSX.</br>

Html-webpack-plugin is also used to automate the procees of creating html in the `./build` folder according to the template `./src/index.html`.</br>

[Basic Manual Setup](../../tree/d95effec5efa2f3b12445bcd0ad2074a167e0a73)
