Next.js - a fullstack react framework for prodution ready that address the issue that every production ready react app need to solve such as Authenitication, Backend

### Features


#### Server-side Rendering

- Pre-create html file that contains the actual data which is good for browser optimation
  - The initial html file is no longer an empty file, but the actual html content after react app been render on the client side
- Prevent the loading page of react app that fetch data only after the Javascript code runs


#### File-based Routing

- remove the Router code and the folder `pages` which are sort of duplication of each other and is basically an illusion of actual routing
- move back to the original state of web dev for routing


#### Fullstack Capabilities

- easily add backend code to Next/React App
- storing data, getting data, authenticaiton etc, can be added to the project