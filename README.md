# File Validator
This project allows you to make a request to an API endpoint and validate the response with a JSON file.
It is designed to be a no-code/low-code solution to API testing. It will make the comparison between the request
response and the expected response.

Since most responses come back as JSON and XML these will be the main file types to compare against.
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

### Todo
- Add support for dynamic fields in responses (e.g., timestamps, IDs). Use placeholders or regex patterns to handle these cases.
- Provide detailed error messages when validation fails, highlighting mismatched fields.
- Extend support to other formats like YAML or plain text for broader use cases.
- Add support for API authentication (e.g., API keys, OAuth) to test secured endpoints.
- Integrate with CI/CD pipelines to automate API testing
- Add validation for the CSV file itself to ensure proper formatting and required fields.
- FUTURE VISION: Consider building a simple UI for non-technical users to upload CSV files and view results.
- Add support for batch testing multiple APIs simultaneously. Possibly offering some type of XML setup file instead of a .csv