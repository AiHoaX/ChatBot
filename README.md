# ChatBot
- The basic implementation of the simple chatbot in python

## Installation
Your Preference => {```conda``` or ```venv```}

```
    mkdir projects
    cd projects
    python3 -m venv venv
```

You need to install nltk

- Installation of nltk

    ```
    pip install nltk
    ```

    If you get an error on run, you need to do:

- Install
``` 
nltk.tokenize.punkt
```
- Run in your terminal
    ```
    $ python
    >>> import nltk
    >>> nltk.download('punkt')
    ```



### Activate in Windows
```
venv\Scripts\activate
```

## Usage

Run
```
python train.py
```

This will dump the ```data.path``` file and then run.
```
python chat.py
```
