# How to set test name for automation test in Pytest on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Pytest-set-testname)

To set test name for automation test in Pytest on LambdaTest, the following steps can be followed. You can refer to sample test repo [here](https://github.com/LambdaTest/pytest-selenium-sample).

## Steps

To set test name as method name in Pytest, the following line can be added to driver function in the`conftest.py` file (full code can be referred in `conftest.py`):

```python
test_name  =  request.node.name
```

### Run your test

```bash
cd tests //navigate to tests directory
python sample_todo.py
```

# Links:

[LambdaTest Community](http://community.lambdatest.com/)


