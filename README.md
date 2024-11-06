This repository contains automated API tests for the Dog CEO API. The tests were created using Postman to verify the functionality of the endpoint that provides information about dog breeds.
Task Description
The main goal of the task was to:
Make a request to the endpoint to retrieve the list of dog breeds.
Validate the status code, schema, and perform data validation for the response.

API Tested
Endpoint: https://dog.ceo/api/breeds/list/all
This endpoint returns a list of all dog breeds.


Implemented Tests
Status Code Validation
Ensures that the response status code is 200 indicating success.

Schema Validation
Checks if the JSON structure of the response matches the expected format.

Data Validation Tests
Breeds List is Not Empty: Verifies that the list of breeds contains at least one breed.
Verify Specific Breed Exists: Ensures that a specific breed (e.g., labrador) is present in the response.
All Breeds Are Unique: Validates that all breed names are unique.
Sub-breeds Structure Is Valid: Confirms that the sub-breeds are in the correct format and the structure is valid.


Bonus Tests
Additional Data Validation
Checked that the list of all breeds is unique.
Verified the correct structure for sub-breeds.


How to Run the Tests
Clone this repository to your local machine;
Import the Postman collection into Postman;
Run the collection using the Postman Runner.



