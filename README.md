# Project #2 - RESTful Booker API Project (restful-booker.herokuapp.com)

# Overview
The RESTful Booker API is a simple API that allows users to create, retrieve, update, delete, and partially update bookings. It also supports user authentication. This project contains test cases for verifying the functionality, security, and performance of the API.

Test plan and test cases for

Test plan
Test cases
https://drive.google.com/drive/folders/1rKEjG5RheY0HMSKhxAHNPDPB6Ry0sKI6?usp=sharing

image

API Documentation
The complete API documentation can be found here.

Endpoints
Health Check: GET /ping
Create Booking: POST /booking
Get Booking: GET /booking/{id}
Update Booking: PUT /booking/{id}
Partial Update Booking: PATCH /booking/{id}
Delete Booking: DELETE /booking/{id}
Create Token: POST /auth
Setup
Prerequisites
Postman
JMeter
OWASP ZAP
Running the Tests
Clone the repository:

git clone https://github.com/your-username/restful-booker-api.git
cd restful-booker-api
Setup Postman: o Import the Postman collection and environment from the postman directory. o Run the collection to execute the test cases.

Run Performance Tests: o Open JMeter and load the test plan from the jmeter directory. o Execute the test plan to run performance tests.

Run Security Tests: o Open OWASP ZAP. o Import the ZAP project from the zap directory. o Run the security scan.

Contribution
Author: Arjun Pramanik
