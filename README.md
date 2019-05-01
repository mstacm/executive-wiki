# executive-wiki
Wiki for ACM Executive Board to help with running ACM. The live version can be
found at
[http://executive-wiki.readthedocs.io](http://executive-wiki.readthedocs.io).

## Building the Documentation
+ Install [Python 3](https://www.python.org/downloads/)
+ Install pipenv
```
pip install pipenv
```
+ Enter the virtual environment
```
cd <github-repo>/
pipenv shell
```
+ Install dependencies
```
pipenv install
```
+ Build the documentation
```
make html
```
+ Open the documentation in your web browser. Should look like:
![documentation](imgs/documentation.png)
