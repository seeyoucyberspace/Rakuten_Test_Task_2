# Dog CEO API Automated Tests

This repository contains automated API tests for the [Dog CEO API](https://dog.ceo/dog-api/). The tests were created using Postman to verify the functionality of the endpoint that provides information about dog breeds.

## Task Description

The main objectives of these tests are:

- Retrieve the list of dog breeds from the API endpoint.
- Validate the response status code, schema, and data.

## API Tested

**Endpoint:** `https://dog.ceo/api/breeds/list/all`

This endpoint returns a list of all available dog breeds.

## Implemented Tests

### Status Code Validation

- Ensures that the response status code is `200` (Success).

### Schema Validation

- Checks if the JSON structure of the response matches the expected format.

### Data Validation Tests

- **Breeds List is Not Empty**: Verifies that the response contains at least one breed.
- **Verify Specific Breed Exists**: Checks that a specific breed (e.g., `labrador`) is present.
- **All Breeds Are Unique**: Validates that all breed names in the response are unique.
- **Sub-breeds Structure is Valid**: Confirms that sub-breeds have the correct structure and format.

### Bonus Tests

- **Additional Data Validation**: Verified that the list of all breeds is unique.
- **Correct Structure for Sub-breeds**: Checked the proper format for sub-breeds.

## How to Run the Tests

1. Clone this repository to your local machine.
2. Import the Postman collection into Postman.
3. Run the collection using the Postman Runner.

Feel free to contribute by adding more tests or improving existing ones!
