
<h1 align = "center"><b><a href = "https://to-do-list-react-application.netlify.app/">To-Do List Application</a></b></h1>

<h2 align = "center"><b>Building a To-Do List Web Application With JavaScript Using React Framework</b></h2>

<p align = "center">
   <img src = "https://github.com/Tanu-N-Prabhu/To-Do-List-React-Application/blob/master/public/FeatureImage.PNG" width="550" height="400">
</p>



# Introduction

<p align = "justify">React is an open-source JavaScript library used for building user interfaces. It is used to handle the “View” layer for web and mobile applications. It also allows us to create reusable UI components. React DOM (Document Object Model) is a virtual DOM that is used for rendering the components of the DOM. The React DOM package has a name that implies is the glue between the React and the DOM. Even though it is a JavaScript library, people often refer to it as a framework, because the fact it has a lot of characteristics of a framework. But it is a JavaScript library, but not a framework. To know more about React.js there is no other place other than its official <a href = "https://reactjs.org/docs/getting-started.html">docs</a>.</p>

---
# Project Set-Up

1. To **create a new React App** navigate to the Visual Code Terminal and type the following command 

   `npx create-react-app project-name` for example `npx create-react-app first-react-app`
   
   On executing the above command will install **four packages** such as `react`, `react-dom`, `react-scripts` and `cra-templates`.
   
2. After getting the success message **Happy Hacking** you now want to execute two commands to change the path or directory and start the server
   
   `cd name_of _project/` for example `cd first-react-app` and 
   
   `npm start` or sometimes `yarn` is preferable

3. Later you will be prompted by the React Home page as shown below - Indication of Successful installation

   <img src = "https://github.com/Tanu-N-Prabhu/To-Do-List-React-Application/blob/master/public/reacthomepage.PNG" width="700" height="400">
   
   > Click on the local host link to view the above result.

4. Add the project to the workspace to see the folders

   > Files --> Add Folders to the Workspace --> Select your React Project Folder

---

# Figma

## Prototype of the application designed by using the Figma Tool.

<img src = "https://github.com/Tanu-N-Prabhu/To-Do-List-React-Application/blob/master/public/To_Do_List_React_App.png" width="700" height="400">



---

# Installation

## Installing Prerequisite Tools for the Project


1. <b>Visual Studio Code</b>
   
   Visual Studio Code is used as a code editor for this project.

   [Download](https://code.visualstudio.com/download) here. 

   ><b>Note</b>: Available for Windows, Mac and Linux.

2. <b>Node.js</b>
   
   Node.js is used for Run time. 

   [Download](https://nodejs.org/en/download/) here. 

   ><b>Note</b>: LTS and Current versions are available. LTS is the stable version. The current is the latest updated version but it’s not stable. We often recommend the LTS version.

3. <b>Figma</b>

   Used as a vector graphics editor and primarily web-based prototyping tool, with additional offline features enabled by desktop applications for macOS and Windows. 

   [Download](https://www.figma.com/downloads/) here.
   
   ><b>Note</b>: Available for Windows and Mac OS, with both online (web-based) and desktop downloading options.
   
---

# Deployment

## Netlify is used to deploy the project on the internet

1. Create and set-up an Account in [Netlify](https://www.netlify.com/)
2. In your Visual Code Terminal Stop the Server using `Ctrl-C`
3. To create a production build use `yarn build` or `npm build` use it accordingly.
4. After successfull installations you will get a `build` folder in your project.
5. Install the [Netlify CLI](https://docs.netlify.com/cli/get-started/) from the Visual Studio Code Terminal. 
6. Use the command to install netlify CLI - `npm install netlify-cli -g`
7. Sometimes you might get an error as `ps1 cannot be loaded because running scripts is disabled on this system`.
8. There are multiple ways to [solve](https://stackoverflow.com/questions/41117421/ps1-cannot-be-loaded-because-running-scripts-is-disabled-on-this-system) this. One of the easiest ways is to install Netlify on your <b>Main Command Prompt</b> not the Visual Studio Code one.
9. You need to login to Netlify using `netlify login`. Enter all the credentials to log in.
10. To deploy the project lastly you need to type `netlify deploy`.
11. Make Sure you select "Create and Confugure a new site". Sometimes it will ask your team name (Netlify Team Name).
12. You can choose a random site name or give a custom one. Make sure to give a unique one.
13. Provide the Build Directory as `./build`.
14. The suite would not yet been deployed from the given URL.
15. Go to your Netlify Dashboard to the project. Click on `Site has not yet been Deployed`. Again click on `Deploy Preview` this will unlock the `Preview Deploy` which is a temporary URL. 
16. After viewing the Preview, click on `Publish deploy` option to deploy your project.
17. Now you project is live and deployed on the internet. 
   

---

# GitHub Commands
Use the Git commands from the Visual Studio Code to either push, commit and pull to the GitHub Repository.

1. `git remote add origin add-your-git-link` - To connect to your GitHub Repository

2. `git add README.md` - To specifically add new files

3. `git commit README.md -m "Fixed the Typo"` - To commit file changes with a message 

4. `git push -u origin master` - To push the changes to the repository

5. `git pull origin master` - Before committing or pushing always pull the changes

6. `rm .git/index.lock` - Use the below command in the root directory of the application. This will delete the index.lock file and release the active lock


---

# Quiz

1. JSX full form in React?

   - [ ] Java Standard XML
   - [x] JavaScript XML
   - [ ] JavaScript XCode

2. React is a?

   - [x] JavaScript Library
   - [ ] Framework
   - [ ] Standalone Desktop Application

3. How many tags we can return in a functional component?
   
   - [ ] Less than 1
   - [ ] More than 1
   - [x] Absolutely 1

4. Which one is a default import?
   
   - [ ] export {App} from "./App.js"
   - [x] import App from "./App.js"
   - [ ] import {App} from "./App.js"
   - [ ] export App from "./App.js"
   
   
5. Which hook is used to maintain the state?

   - [ ] `useEffect()`
   - [ ] `useRef()`
   - [ ] `useCallback()`
   - [x] `useState()`
   
6. EventListener is a?

   - [x] function
   - [ ] attribute
   - [ ] props
   
7. Which function is use to remove an item?
 
   - [ ] map
   - [ ] delete
   - [x] filter
   
8. Which one of them is a spread operator?

   - [ ] .
   - [ ] ..
   - [x] ...
   
   
---
   
# Credits

1. <b>Udemy Course</b> - [React JS from absolute scratch by building your first React web app](https://www.udemy.com/course/react-the-beginners-course/learn/lecture/20514796#content)

   > Thanks to  [Anton Francis Jeejo](https://www.udemy.com/user/anton-francis-jeejo/)

