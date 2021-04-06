# aws_lambda_py3_zip
Zip file with pandas library, to use in amazon lambdas.


## Include libraries:

- boto3
- s3fs
- numpy
- pandas

## Use
To add main.py and other files use:

`zip -ur zip.zip main.py
`

Upload file to s3, because file is too large. 
Then, create lambda function from s3 path.

## Requirements

Should be run with python 3.7