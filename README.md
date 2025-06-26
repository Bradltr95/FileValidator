# File Validator
This project allows you to make a request to an API endpoint and validate the response with a JSON file.
It is designed to be a no-code/low-code solution to API testing. 
### How To Get Started
Open the sample .csv file under src/main/resources/validators called
sampleValidator.csv. 

### How To Use the CSV
There are 3 fields total. The idea behind the csv is as follows.

- Field 1: Add the API endpoint you with to test in the following format:
1. GET https://google.com
2. POST https://sampleloginpage.com

- Field 2: A blank field with a place to add a description about the test.
- Field 3: The name of the file with the expected response. 

### How to Handle Dynamic Fields
This is something we will have to consider moving forward. For now it expects
basic, simple requests. 