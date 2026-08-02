🚀 API Testing Project
 
📌 Project Overview:

This project demonstrates REST API Testing using Postman and Newman. It includes API request execution, automated test scripts, environment variables, and Newman report generation for validating API functionality.

🛠️ Tools & Technologies:

 1. 📮 Postman
 2. ⚡ Newman
 3. 📄 HTML Extra Reporter
 4. 📜 JavaScript (Postman Test Scripts)

 📂 Project Structure:
 
 1.  CollectionforAPI.json
 2.  EnvironmentforAPI.json
 3.  API_Report_newman.html
 4.  README.md

📋 API Collection:

 The project contains 9 API requests:
 1. GetBookingIds-------------GET  Method
 2. CreateBooking-------------POST Method
 3. GetSpecificBookingId------GET Method
 4. CreateToken---------------POST Method
 5. UpdateBooking-------------PUT Method
 6. PartialUpdateBooking------PATCH Method
 7. GetUpdatedBooking---------GET Method
 8. DeleteBooking-------------DELETE Method
 9. GetSpecificBookingId----GET Method (Verify Deleted Booking)

🌍 Environment Variables:

 The collection uses the following environment variables:
 1. base_url--------->API Base URL
 2. bookingid--------->Booking ID
 3. token------------->Authentication Token
 4. fname------------->First Name
 5. lname------------->Last Name
 6. tprice------------>Total Price
 7. dpaid------------->Deposit Paid
 8. checkin----------->Check-in Date
 9. checkout---------->Check-out Date
 10. additionalneeds-->Additional Needs

 ✅ Test Assertions: 
 
 1. Status Code Validation
 2. Response Time Validation
 3. Response Size Validation
 4. Response Format Validation
 5. Data Validation

 📊 Newman Execution Summary:
 The Newman report shows the following execution summary:
 1. Total Requests
 2. Total Iterations
 3. Total Assertions
 4. Failed Tests
 5. Skipped Tests

📈 Report:

The collection was executed using Newman, and an HTML report was generated. 
 
 Report File:
 "API_Report_newman.html"

▶️ How to Run:
1. Import Collection:
  a. Open Postman
  b. Import the Collection
  c. Import the Environment
2. Run Collection:
  a. Select the Environment
  b. Click Run Collection

Run Using Newman:

newman run CollectionforAPI.json -e EnvironmentforAPI.json -r htmlextra --reporter-htmlextra-export API_Report_newman.html

📌 Expected Outcome:
1. All API endpoints execute successfully.
2. Assertions validate response correctness.
3. Newman generates an HTML report.
4. Failed assertions can be analyzed for debugging and improvement.

👩‍💻 Author:

Tasmin Jannat Tahsin
