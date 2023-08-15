# Passenger_Rest_API
## How to run this project
* Clone this project
* Open with Postman / Command Shell
* Run Command:
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
```
* Run Command for Report:
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra 
```


## Technology Used:
* Postman
* Newman

## Prerequisite:
* Jdk
* Node Js
* Newman
* HTML Report Library

## Newman and Report Installation Process:
* Newman Install Command:
```console 
npm install -g newman-reporter-htmlextra
```
* Newman Html Report Install Command:
```console 
npm install -g newman-reporter-htmlextra
```
## API Documentation:
* https://restful-booker.herokuapp.com
## Test case list:
1. ### Create Booking
	> Used POST method for creating Data Sets Using the Dynamic Random Variables.
2. ### Verify Created Booking Details
	> Used GET method
  > In the test case validate the following field values:
 	1. > First Name
 	2. > Last Name
 	3. > Total Price
 	4. > Deposit Paid

3. ### Create Token
	> Used POST method
  > A token has been created
4. ### Update Booking
	> Used POST method
  > In the test case validate the following field values:
	1. > First Name
 	2. > Last Name
	3. > Total Price
 	4. > Deposit Paid
  5. > Checkin
  6. > Checkout
     
8. ### Delete Specific Booking
	> Used the DELETE method 
## Newman Report Summary:
![Report](https://github.com/Anika154/Customer_Details_Rest_API/assets/54212195/91043030-3b8c-4da0-ae28-b519a1cee6e5)
![Report](https://github.com/Anika154/Customer_Details_Rest_API/assets/54212195/a6a3a781-7502-4776-860b-4f35f0e4be28)











  
