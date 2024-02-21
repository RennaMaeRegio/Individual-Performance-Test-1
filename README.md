# Individual-Performance-Test-1
Performance Test Instructions
Objective:
The performance test aims to evaluate your ability to retrieve, sort, and select backend courses data according to specified requirements.

Steps:
Download and Install MongoDB Database Tool:

Download the MongoDB Database tool from here.
Follow the installation instructions provided here.
Create Backend API Endpoint:

Use the following command to import the provided course data:
css
Copy code
mongoimport --db mongo-test --collection courses --file courses.json --jsonArray
Test Procedure:

Retrieve all published backend courses and sort them alphabetically by their names.
Select and extract the name and specialization of each course.
Retrieve all published BSIS (Bachelor of Science in Information Systems) and BSIT (Bachelor of Science in Information Technology) courses from the curriculum.
Perform data validation at each step to ensure the accuracy and integrity of the retrieved information.
Document the test procedure, including any challenges faced and solutions implemented.
Additional Notes:
Ensure that MongoDB Database Tool is correctly installed and configured before proceeding with the test.
Double-check the commands used for importing data and ensure that they are executed accurately.
Pay close attention to the sorting and filtering criteria specified in the objective to accurately retrieve the required information.
Note: This README serves as a guide for conducting the performance test. Make sure to follow the instructions meticulously and document any issues or resolutions encountered during the testing process.
