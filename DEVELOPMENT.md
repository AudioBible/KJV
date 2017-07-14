## ![stats](https://c.statcounter.com/11394987/0/efc40f08/0/) Welcome to [http://audiobible.life](http://audiobible.life) - [KJV](https://github.com/AudioBible/KJV) - [AudioBible](https://github.com/AudioBible/AudioBible) - Therefore Choose Life

[README](README.md) | [USAGE](USAGE.md) | [HELP](HELP.md) | [DEVELOPMENT](DEVELOPMENT.md) | [CHANGES](CHANGES.md) | **We The People** | **Have The Power** | **Don't Be A Clown**

[VIDEOS](VIDEOS.md) | [MUSIC](MUSIC.md) | [CHANNELS](MUSIC.md) | [DOCUMENTS](DOCUMENTS.md) | [IMAGES](IMAGES.md) | [BOOKS](BOOKS.md) | [LINKS](LINKS.md) | [INFO](INFO.md) | **Join The Revolution**

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
