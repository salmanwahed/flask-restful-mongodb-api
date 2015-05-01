# flask-restful-mongodb-api
REST api using flask-restful and MongoDB

### Install requirements: ###
Install the requirements in a virtual environment.
```
pip install -r requirements.txt
```
### Testing api ##
Api can be tested in several ways. Python [requests](http://docs.python-requests.org/en/latest/) module example:
```pyhton

In [1]: from requests import get, post, put, delete
In [2]: get("http://127.0.0.1:5000/api")
In [3]: data = {"name": "Example Name", "registration": "123433199", "department": "cse"}
In [4]: post("http://127.0.0.1:5000/api", json=data)

```


