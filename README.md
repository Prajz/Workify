# Workify
Project for Software Processes and Modelling Coursework. Compares data on Spotify listening habits and productivity to help users improve their work habits.

## Python Packages
Install required python packages
```powershell
pip install -r requirements.txt
```
## File Structure
<pre>
.
├── Unit Tests
│   └── database_test.py        # Unit tests for the database
├── Webapp
│   ├── static
│   │   ├── scripts             # JS
│   │   └── styles              # CSS
│   ├── templates               # HTML templates   
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── landing_page.html
│   │   └── temp.html
│   ├── utils                   # Additional python classes
│   │   ├── database_utils.py
│   │   ├── music_utils.py
│   │   └── url_utils.py
│   ├── main.py                 # Flask application  
│   ├── views.py                # Flask application views and routes
│   ├── db_schema.py            # Python classes wrapped to sqlite database 
│   ├── requirements.txt        # Specifies required python packages 
│   └── workify.sqlite
└── README.md