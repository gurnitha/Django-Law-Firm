# Django Law Firm
Membuat aplikasi Law Firm menggunakan Django versi 2.2


## 1. SETUP

#### 1. SETUP - modified .gitignore and readme.md files

        modified:   .gitignore
        modified:   README.md


#### 2. SETUP - checking python and pip versions

        hp@ING:DjLawFirm ~ python -V
        Python 3.9.5

        hp@ING:DjLawFirm ~ pip -V
        pip 23.1.2 from C:\python\Python39\lib\site-packages\pip (python 3.9)
        

#### 3. SETUP - create virtual environment


        ing@ing:/mnt/f/_ingafter65/Django-Law-Firm$ tree -d
        .
        ├── _docs
        └── venv3942
            ├── Include
            ├── Lib
            │  └── site-packages
            ... 
            └── Scripts
        

#### 4. SETUP - activate venv3942

        hp@ING:DjLawFirm ~ venv3942\Scripts\activate

        (djlawfirm) hp@ING:DjLawFirm ~
        

#### 5. SETUP - install django version 4.2

        (djlawfirm) hp@ING:DjLawFirm ~ pip install django==4.2
        Collecting django==4.2
          Using cached Django-4.2-py3-none-any.whl (8.0 MB)
        Collecting sqlparse>=0.3.1
          Using cached sqlparse-0.4.4-py3-none-any.whl (41 kB)
        Collecting tzdata
          Using cached tzdata-2023.3-py2.py3-none-any.whl (341 kB)
        Collecting asgiref<4,>=3.6.0
          Using cached asgiref-3.7.2-py3-none-any.whl (24 kB)
        Collecting typing-extensions>=4
          Using cached typing_extensions-4.7.1-py3-none-any.whl (33 kB)
        Installing collected packages: typing-extensions, tzdata, sqlparse, asgiref, django
        Successfully installed asgiref-3.7.2 django-4.2 sqlparse-0.4.4 typing-extensions-4.7.1 tzdata-2023.3
        WARNING: You are using pip version 21.1.1; however, version 23.1.2 is available.
        You should consider upgrading via the 'f:\_ingafter65\django-law-firm\venv3942\scripts\python.exe -m pip install --upgrade pip command.

