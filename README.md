#### Python CRUD

##### Set-up
```terminal
$ brew install python
$ sudo easy_install pip
$ virtualenv venv
$ pip install Flask
$ gitignore python

// errors installing pip so uninstalled, and re-installed
$ sudo pip uninstall pip
```

##### python-route.py fiel
```terminal
$ nano python-route.py
```
```nano
from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'

if __name__ == '__main__':
        app.run()

```
