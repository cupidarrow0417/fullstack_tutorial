# FullStack Tutorial

- Author: Jack Jiang
- Date: Jul. 2019

[![](https://img.shields.io/badge/managed%20by-ppm-red)](https://jiangyiqun.github.io/ppm/)

In this fullstack tutorial, I will implement a simple CRUD App, including:
- A [Frontend](https://jiangyiqun.github.io/fullstack_tutorial/) using [JavaScript(React)](https://reactjs.org/)
- A [Backend](./docs/README.md) using [Python(Flask)](https://flask.palletsprojects.com/en/1.1.x/)

___

## Create Frontend from scratch

### Prerequisite

- [Node.js](https://nodejs.org)

### Create React App

```shell
npx create-react-app frontend     # create basic react app
cd frontend
npm install --save reactstrap     # install essitial modules
```

___

## Create Backend from scratch

### Prerequisite

- [Anaconda (Python 3)](https://www.anaconda.com/distribution/#download-section)

### Create Flask App

```shell
mkdir backend
cd backend
python3 -m venv python_modules          # create python environment
source ./python_modules/bin/activate    # activate python environment
pip install flask flask-cors     		# install essitial modules
python -m pip freeze > package-lock.txt		# save dependencies to package.txt
deactivate                              # deactivate python environment
```

**Alternatively, you could use [ppm](https://github.com/Jiangyiqun/ppm) (no available for Windows)**

```shell
mkdir backend
cd backend
ppm install
ppm install flask flask-cors           # install essitial modules
```
