# ibsc

## How to use this repo

1. Install vanialla python from here: https://www.python.org/downloads/
2. install pipenv `pip install pipenv`
3. clone this repo 
4. Create a new branch to work on all the changes.
5. to start a virtual environment use
`pipenv shell ` which will create the environment and activate it if there is a pipfile in the current folder


## Debug mode

-  To run flask in debug mode, we have to define a environment variable
    * windows(powershell)
    `$env:FLASK_ENV = "development"`
    * windows(cmd)
    `C:\path\to\app>set FLASK_ENV=development`
    * mac
    `$ export FLASK_ENV=development`
    
## Run application

flask run


