# A peek into pandas 

## Purpose 
This repo was created to allow quick setup and demonstration of various Pandas features.
It is structured around using `VsCode` and its `Visual Studio Code Remote - Containers` extention so that anyone with a PC and minimal abilities can get the code to run, change it and, all together, have a good time WO messing around local development env issues.

## How
### Install stuff
On your PC:
* make sure Docker Desktop is installed and running [link](https://docs.docker.com/desktop/install)
* make sure VsCode is installed too: [link](https://code.visualstudio.com/download)
* once VsCode is installed, install the Remote-Containers extensions: [link](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
* clone this git repo, run this line in the directory to which you want to save the code samples. 
```bash
git clone https://github.com/itamar-otonomo/pandas_tutorial.git
```

### Open in VsCode

* Start Visual Studio code.
* Go to File -> Open Folder and browse to the folder of the repo. Click on the `pandas_tutorial` directory and click Open
* When asked (lower right of screen) if you want to open the code in the dev-container, click Yes
* First run would take some time. once the docker image is built you would enter the dev environment and you are good to go.
