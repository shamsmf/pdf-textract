<h1>PDF FORM READER<h1>

This project is designd in pyhton language to read a pdf file and extract field values into spreadsheet.
It will return the file path of the xlsx file.

####Installation
PDF Form reader requires Python 3.6.9 to run.

#####Install the requirements:
```
pip install -r requirements.txt
```

#####Set credentials in the AWS credentials profile file on your local system, located at:
~/.aws/credentials on Linux, macOS, or Unix.

C:\Users\USERNAME\.aws\credentials on Windows

This file should contain lines in the following format:
```
[default]
region=your_region
aws_access_key_id = your_access_key_id
aws_secret_access_key = your_secret_access_key
```

#####Replace S3 Bucket details
Where input pdf files will be stored.
```
s3BucketName = awss3_bucket_name
```

#####Run the project:
```
python3 code_file.py
```

#####Enter the pdf file full path as input.

It will return the out xlsx file path.
File Path: ./input_sheet_output.xlsx

Reference: [Amazon Textract](https://docs.aws.amazon.com/textract/latest/dg/what-is.html)

