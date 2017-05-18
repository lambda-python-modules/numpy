# NumPy for AWS Lambda
This is binary module of NumPy which is compatible with AWS Lambda. It's basically original NumPy Wheel [1] clone to simplify its use inside Lambda.

# Usage
Just clone this repository to your Lambda function's root folder and you can import numpy. Please note that NumPy is more that 10Mb so you cannot upload it to the Lambda directly. Please use S3 bucket instead.

```
$ cd /path/to/lambda/function
$ git clone https://github.com/lambda-python-modules/numpy.git ./numpy
```

# References:
[1] https://pypi.python.org/pypi/numpy
