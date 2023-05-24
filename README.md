# Simple-program
This is simple python end to end program by using FLASK and deployed in HEROKU cloud.

create a new virtual environment
```
conda create -p venv -y python==3.11.3
```

activate that virtual environment
```
conda activate venv/
```

 create file <filename.py>  
 
 import the Flask module 
 ```
 pip install flask
 ```

 type the below program in the python file 

 ```
 from flask import Flask, request

app= Flask(__name__)

@app.route('/', methods=['GET', 'POST'])
 
def hel():
    return 'HELLO WORLD'

if __name__=='__main__':
    app.run(debug=True)

```

to add these file to git 

```
git add .
```

to commit git

```
git commit -m <"commit statement">
```

to pust git

```
git push
```


