# [particles-js-first-app]()

<br />
<img src="" alt="particles.js first app" width="800">
<br />

---

# Table of Contents <a name="tableOfContents"></a>

1. [Introduction](#introduction)

2. [Run the project locally](#runLocally)

3. [Deployment](#deployment)
	- [Deployment – Run locally](#deploymentRunLocallydeploymentRunLocally)
	- [Deployment – Live website](#deploymentLiveWebsite)

4. [Credits](#credits)
	- [Media](#media)
---

## Introduction <a name="introduction"></a>

## Run the project locally <a name="#runLocally"></a>

Install Node.js five-server, a development server with live reload capability. 

  - To install:
    
    ```
      # Remove live-server (if you have it)
      npm -g rm live-server

      # Install five-server
      npm -g i five-server
    ```

  - To update (from time to time)
        
    ```
      # Update five-server
      npm -g i five-server@latest
    ```

  - To run (from your local directory):
        
    ```
    five-server . -p 8000
    ```

  - Plugins for popular code editors
  Some code editors have plugins which will spawn a simple server on demand.

      - [Five Server](https://marketplace.visualstudio.com/items?itemName=yandeu.five-server) for Visual Studio Code.
      - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for Visual Studio Code.
      - [Live Server](https://atom.io/packages/atom-live-server) for Atom.

Back to [top](#tableOfContents)

---

## Deployment <a name="#deployment"></a>

### Deployment – Run locally <a name="#deploymentRunLocally"></a>

1. Prerequisite:  
    - Make sure [Node](https://nodejs.org/en/) and [NPM](https://www.npmjs.com/) are installed on your computer. You can download both at nodejs.org (NPM is included in your Node installation).  
    - Please see `.nvmrc` file at the root of `particles-js-first-app` repo.  
    - Using nvm, a Node Version Manager is recommended as it helps you manage and switch between different Node versions with ease. It provides a command-line interface where you can install different versions with a single command, set a default, switch between them, etc.
2. Install the [particle.js](https://www.npmjs.com/package/particles.js) npm module, open a terminal window in your project folder and run:
  
    ```
      npm install particles.js
    ```

3. In GitHub click on the repository nammed [particles-js-first-app](https://github.com/sctlcd/particles-js-first-app)
4. Along the top bar, find the “clone or download” button.
5. Here you have the option to clone by HTTPS or SSH.
6. Once you have chose your desired option, then click the copy icon next to the URL.
7. In the terminal, ensure you are in the correct directory which you want to copy the code into. If not, change the directory.
8. Run 

    ````
    $ git clone https://github.com/sctlcd/particles-js-first-app.git
    ````

9. Press the enter button and your clone will be created.
10. Install Node.js five-server, a development server with live reload capability. 

  - To install:
      
      ```
        # Remove live-server (if you have it)
        npm -g rm live-server

        # Install five-server
        npm -g i five-server
      ```

  - To update (from time to time)
      
      ```
        # Update five-server
        npm -g i five-server@latest
      ```

  - To run (from your local directory):
      
      ```
      five-server . -p 8000
      ```

  - Plugins for popular code editors
  Some code editors have plugins which will spawn a simple server on demand.

      - [Five Server](https://marketplace.visualstudio.com/items?itemName=yandeu.five-server) for Visual Studio Code.
      - [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for Visual Studio Code.
      - [Live Server](https://atom.io/packages/atom-live-server) for Atom.

Back to [top](#tableOfContents)

---

### Deployment - Live Website <a name="#deploymentLiveWebsite"></a>

[particles-js-first-app](https://github.com/sctlcd/particles-js-first-app) live website is currently deployed on [GitHub pages](https://pages.github.com/) using the `main` branch on GitHub. Once you have the project setup locally, you can proceed to deploy it remotely.

1.	In GitHub click on your repository to open it.
2.	Find the 'settings' tab and click on it.
3.	In the left menu select 'Pages'
4.	In Build and deployment section, under 'Source' choose a branch `Deploy from a branch`, under Branch chose `main` and `/(root)` then press the Save button
5.	Wait a couple of minutes and refresh the page then you will see a URL to your live site. In my case the URL is https://sctlcd.github.io/particles-js-first-app/

Back to [top](#tableOfContents)

---

## Credits <a name="credits"></a>

### Media <a name="media"></a>

- []() - []() | copyright []()

Back to [top](#tableOfContents)

---