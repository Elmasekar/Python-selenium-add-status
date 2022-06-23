# How to add test status in automation test in Python-selenium on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Python-selenium-add-status)

If you want to add test status in automation test in Python-selenium on LambdaTest, you can follow the below steps. You can refer to sample test repo [here](https://github.com/LambdaTest/python-selenium-sample).

## Configure testcase

After the execution of a testcase, you have to execute a script (lambda-status) to pass "passed" or "failed" based on the execution. See the example code below:


```python

#testcase pass condition
if(testcase_pass = True):
	driver.execute_script("lambda-status=passed")

	print("Tests are run successfully!")
else:
	driver.execute_script("lambda-status=failed")
```

## Run your test

```bash
python lambdatest.py
```


# Links:

[LambdaTest Community](http://community.lambdatest.com/)

