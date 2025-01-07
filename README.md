# POS Malaysia API Automation

This repository contains the Postman collection and environment configuration for automating the testing of POS Malaysia APIs. Follow the steps below to set up the collection and run it on your local machine.

## Prerequisites

1. **Postman**: Ensure you have Postman installed on your system. You can download it from [Postman Official Website](https://www.postman.com/downloads/).
2. **Git**: Make sure Git is installed to clone this repository. [Install Git](https://git-scm.com/).

## Files in This Repository

- **`POS Malaysia API's.postman_collection.json`**: The Postman collection file containing all the API requests and tests.
- **`POS Malaysia.postman_environment.json`**: The Postman environment file containing variables required for running the APIs.

## Setup Instructions

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Adnan-Aashiq/POS-APIs-Testing.git
   ```

2. Open Postman and import the collection and environment files:
   - **Import Collection**:
     1. Go to the **Collections** tab in Postman.
     2. Click on **Import**.
     3. Select the file `POS Malaysia API's.postman_collection.json` from the cloned repository.
   - **Import Environment**:
     1. Go to the **Environments** tab in Postman.
     2. Click on **Import**.
     3. Select the file `POS Malaysia.postman_environment.json` from the cloned repository.

3. Select the imported environment:
   - Click on the **Environment dropdown** in the top-right corner of Postman.
   - Select the **POS Malaysia** environment.

## Running the Collection

1. Navigate to the **Collections** tab in Postman.
2. Click on the `POS Malaysia API's` collection.
3. Click on the **Run** button to open the Collection Runner.
4. Configure the following settings in the Collection Runner:
   - Select the **POS Malaysia** environment.
   - Set the number of iterations if required.
   - (Optional) Enable or disable specific tests based on your requirements.
5. Click **Run Collection** to execute the tests.

## Notes

- The environment variables are pre-configured for the current API endpoints and test data:
  - **`baseURL`**: API base URL (`https://www-api.pos.com.my/api`)
  - **`perakPostCode`**: Postcode for Perak (`35600`)
  - **`postcodeTo`** and **`postcodeFrom`**: Sample postcodes for testing.
  - **`invalidPostCode`**: Used for negative test cases.
- Tests are included in the Postman collection for:
  - Positive and negative scenarios.
  - Response structure validation.
  - Status code validation.
  - Performance (response time within acceptable limits).

## Contact

If you encounter any issues or have questions, feel free to contact me at **adnanaashiq457@gmail.com** and WhatsApp me on **+92-302-2149193**.

