# Python

```Python3
from flask import Flask, render_template
app = Flask(__name__)

@app.route('/')
def home:
    return render_template()
    
if __name__ == "__main__":

```