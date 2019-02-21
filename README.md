# Python py-test and Travis CI
Testing code for py-test and travis CI

## pytest
test*.py files created from - https://docs.pytest.org/en/latest/getting-started.html#our-first-test-run

"Run multiple tests: pytest will run all files of the form test_*.py or *_test.py in the current directory and its subdirectories. More generally, it follows standard test discovery rules"

```text
pytest supports execution of unittest test cases. The real advantage of pytest comes by writing pytest test cases. pytest test cases are a series of functions in a Python file starting with the name test_.

pytest has some other great features:

Support for the built-in assert statement instead of using special self.assert*() methods
Support for filtering for test cases
Ability to rerun from the last failing test
An ecosystem of hundreds of plugins to extend the functionality
```
* https://realpython.com/python-testing/

## Travis CI
```text
Matching Jobs with allow_failures #

When matching jobs against the definitions given in allow_failures, all conditions in allow_failures must be met exactly, and all the keys in allow_failures element must exist in the top level of the build matrix (i.e., not in matrix.include).
```
* https://docs.travis-ci.com/user/customizing-the-build/

## Anaconda
Update anaconda base to Python 3.7.2
```bash
conda update -n root conda
conda update --all
```
* https://stackoverflow.com/questions/45197777/how-do-i-update-anaconda

up

## Resources
* Building a Python Project - https://docs.travis-ci.com/user/languages/python/
* Test Discovery Good Practices - https://docs.pytest.org/en/latest/goodpractices.html#test-discovery