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
![Screenshot 2023-08-15 223844](https://github.com/Anika154/Passenger_Rest_API/assets/54212195/e09b9bb1-35b0-4446-86c8-7d89e8bfb256)
![Screenshot 2023-08-15 224202](https://github.com/Anika154/Passenger_Rest_API/assets/54212195/be29534e-be3d-4f1b-8643-915a9fb22cbd)














  
