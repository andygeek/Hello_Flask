# Hello World Flask

![](https://img.shields.io/badge/Made%20with-Flask-black) ![](https://img.shields.io/badge/Made%20with-Python-blue) 

It is my fist application in Flask with Python.

![](https://imgur.com/HfgNGlw.png)

## Starting 🚀

These instructions allow you to obtain a copy of the running project on your local machine for development and testing purposes.

### Prerequisites 📋

You need to have install:
- Python 3
- Virtualenv for python

Virtualenv needs to be initialized in the repository file.
````
virtualenv env
````
Then, is necessary to activate viertualenv.
````
source env/Scripts/activate
````

### Installation 🔧

To install dependencies, use the following command.

````
pip install -r requirements.txt
````

### Develop 🖇️

For run app in the development mode add variable enviroment so flask recognize where to start execution.
````
export FLASK_APP=main.py
````
Now to run the application use the following command.
```` 
flask run
````
### Deployment 📦

For deployment in a server use the following command.
````py
python main.py
````
------

⌨️ with ❤️ for [AndyGeek](https://github.com/andygeek) 😊
