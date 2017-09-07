# Basic Application Structure

- Check to see if python is on the path. 

```
echo %PATH%

```
If it isn't, then put the following on command line as temporary:

```
setx PATH "%PATH%;C:\Python34\Scripts"

```

To install a package, do the following:

```

python -m pip install [packagename]

```
- How to initialise the app

```
from flask import Flask
app = Flask (__name__)
```
- Routes and view functions

```
@app.route('/')
def index()
    return '<h1>Hello World!</h1>'

@app.route('/user/<name>')
def user(name):
    return '<h1>Hello, %s!</h1'> % name   
```
- Server Startup

```
if __name__ == '__main__':
    app.run(debug=True)
```

- Dynamic Routes

```
@app.route('/')
def index():
    return '<h1>Hello World!</h1>'
```    
