# MUMBLE

An Open Source Social Media Platform and Public Forum for Questions and Discussions, built for Developers.

## 🔗 Links
- **Live Demo: (https://www.mumble.dev/)**
- **UI Kit (Docs/Preview) 👉 [Here](http://mumble-lp.s3-website-us-west-2.amazonaws.com/)**
- **Discord [Join here](https://discord.gg/TxgpyK8pzf)**
---
## Requirements

For development, you will need Node.js and a node global package, NPM or Yarn, installed in your environement along with a text editor of your choice.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

  If the installation was successful, you should be able to run the following command.
    
      $ node --version
      v12.18.2
      
      $ npm --version
      6.14.8

- #### For Yarn installation
  After installing node, this project will need yarn too, so just run the following command.

      $ npm install -g yarn

---
## Download & Setup Instructions

Clone the project. This will download the GitHub respository files onto your local machine.

```Shell
git clone https://github.com/divanov11/mumble
```

### Frontend Instructions (Create React App)

Navigate to the `frontend/` directory

```Shell
cd Mumble && cd frontend
```

Install the project dependencies

```Shell
npm install
```

Start the development server on localhost:3000

```Shell
npm start
```

## Want to Contribute?

Check out the [contributing guide](https://github.com/divanov11/Mumble/blob/master/CONTRIBUTING.md).

> **_⚠ Those who wants to contribute on the repo, from now, before pushing/committing your changes, please make sure you run command `npm run format` or `yarn format` or use Prettier plugin to automatically format your code. We want to maintain consistency that's why we want to enforce the formatting. It's required!_**

## 📸 Screenshots

**User Feed** : <br/><br/>

<img src="./images/home-page.PNG" width=600 />

**User Profile Page** : <br/><br/>
<img src="./images/profile-page.PNG" width=600 />

**Discussion/Question Page** : <br/><br/>
<img src="./images/discussion-page.PNG" width=600 />

**Login Page** : <br/><br/>
<img src="./images/login-page.PNG" width=600 />
