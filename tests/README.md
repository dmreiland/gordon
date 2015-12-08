How to run all tests?
---------------------

```shell
python setup.py nosetests'
```

How to run unittests?
---------------------

```shell
python setup.py nosetests -a '!integration'
```


How to run integration tests?
------------------------------

```shell
python setup.py nosetests -a 'integration' --stop --nologcapture --processes=3
```

How to run one integration test?
--------------------------------

```shell
python setup.py nosetests -a 'integration' --stop --nologcapture --where=tests/lambdapython/
```