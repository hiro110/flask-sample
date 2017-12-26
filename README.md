# flask-sample
flaskを使ったサンプルアプリ

# Reference
[flaskで簡単なwebアプリ作成](https://qiita.com/yshi12/items/9502c6232e96d7dfa29d)  
[Flask入門](http://www.kzfmix.com/flaski/)


# Requirement

```:
$python -V
Python 3.4.3

$pip freeze
certifi==2017.11.5
chardet==3.0.4
click==6.7
Flask==0.12.2
httpie==0.9.9
idna==2.6
itsdangerous==0.24
Jinja2==2.10
MarkupSafe==1.0
Pygments==2.2.0
requests==2.18.4
SQLAlchemy==1.1.15
urllib3==1.22
Werkzeug==0.13
```

# Directory Tree

```:
.
├── README.md
├── app.py          # Entry Point
├── do_create.py    # Create schema
├── do_insert.py    # Insert Data
├── flaski          # DB Files
│   ├── __init__.py
│   ├── database.py
│   └── models.py
├── static          # Static Files ex) .jpg .png
│   └── snake.jpg
└── templates       # Template Files
    ├── index.html
    ├── layout.html
    └── show_content.html


```