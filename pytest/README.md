# Python 3

Testing with [pytest](https://docs.pytest.org/en/7.1.x/).

1. Add aliases

```
alias python=/usr/local/bin/python3
alias pip=/usr/local/bin/pip3

```
2. Install pytest
```
pip install -U pytest
```

## Selenium test example

3. Create the test in Selenium IDE
4. Example target selector: css=#results-focus > span
   This is not JS or CSS.
5. Export the test to Python.
6. Run **pytest** in the directory with the exported test.

Make sure you have the Chrome and Gecko drivers in a PATH dir ~/bin in the $PATH.