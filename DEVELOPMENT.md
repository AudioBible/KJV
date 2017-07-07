Development
===========

## make some changes and create a pull request

#### download the project using git

    git clone git@github.com:AudioBible/AudioBible.git
    
#### download from your fork so you can create a pull request if you make changes
    
    git clone git@github.com:{USERNAME}/AudioBible.git
    
#### install python package from git cloned project directory

    cd AudioBible
    pip install .
    audiobible

#### change into the project directory and run the program during development
    
    cd AudioBible
    audiobible/__init__.py
    
#### run with books located in ./tests/KJV directory and data located in ./tests
    
    BOOKS_PATH=tests audiobible/__init__.py
    
#### run tests giving the books data path

    BOOKS_PATH=tests python -m unittest tests


- Thank you
