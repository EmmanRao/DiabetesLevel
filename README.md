# DiabetesLevel


## Software and Tools Requirements

1. [Github Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment


'''
    pip install virtualenv
    python -m venv <environment name>
    venv\Scripts\activate
'''

install libraries in new environment

1. [Flask]
2. [pandas]
3. [numpy]
4. [matplotlib]
5. [scikit-learn]

create requirements file 
'''
pip freeze > requirements.txt
'''

set global email and user name for git cli
'''
git config --global user.name "user name of github"
git config --global user.email "emain id on which github account is attached"
'''


import libraries
create app 
load pickle files
load scaling file
create @app.route
def function
create predict api
    request
    read data from json 
    then reshape
    then transform
    then model.predict
    then return
create predict function
    request
    read data from json and form
    then reshape
    then transform
    then model.predict
    then return

now to run app 
'''
if __name__=="__main__":
    app.run(debug=True)
'''