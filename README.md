<h1>PDF FORM READER</h1>

This project is developed using python to read a pdf file and extract field values into a spreadsheet.
It will return the file path of the xlsx file.

<h4>Installation<h4>
PDF Form reader requires Python 3.6.9 to run.

<h5>Install the requirements:</h5>
```
pip install -r requirements.txt
```

<h5>Set credentials in the AWS credentials profile file on your local system, located at:</h5>
~/.aws/credentials on Linux, macOS, or Unix.

C:\Users\USERNAME\.aws\credentials on Windows

This file should contain lines in the following format:
```
[default]
region=your_region
aws_access_key_id = your_access_key_id
aws_secret_access_key = your_secret_access_key
```

<h5>Replace S3 Bucket details</h5>
Where input pdf files will be stored.
```
s3BucketName = awss3_bucket_name
```

<h5>Run the project:</h5>
```
python3 code_file.py
```

<h5>Enter the pdf file full path as input.</h5>

It will return the out xlsx file path.
Example input_form_a.pdf and input_form_b.pdf files are available in the folder input-pdfs.
The third file, output_values.png highlights the values need to extract from the sample statements.
File Path: ./input_sheet_output.xlsx

Reference: [Amazon Textract](https://docs.aws.amazon.com/textract/latest/dg/what-is.html)

