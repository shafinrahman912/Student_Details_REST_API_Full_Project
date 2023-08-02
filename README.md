# Student_Details_REST_API_Full_Project


## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/28551467/2s9XxwutCj

## Test case list:
1. ### Get All Students List
	> Validation of status code and the length of student list in the test case.
 	1. > Validating Status Code
 	2. > Validating the Length of Student List
2. ### Create Student
	> Create Data Sets Using the Dynamic Random Variables and validation of status code in the test case.
	1. > Validating Status Code
3. ### Verify Created Student Details
	> Validation of the following field values in the test case :
 	1. > Validating First Name
 	2. > Validating Middle Name
 	3. > Validating Last Name
 	4. > Validating Date of Birth
 	5. > Validating Status Code 

4. ### Update Student
	> Validation of the following field values in the test case :
 	1. > Validating First Name
 	2. > Validating Middle Name
 	3. > Validating Last Name
 	4. > Validating Date of Birth
     
5. ### Verify Updated Student Details
	>  Validation of the following field values in the test case :
	1. > Validating First Name
 	2. > Validating Middle Name
	3. > Validating Last Name
 	4. > Validating Date of Birth

6. ### Create Technical skills 
	> Validation of status code in the test case :
	1. > Validating Status Code

7. ### Create a Student Address
	> Validation of status code, message and status in the test case :
	1. > Validating Status Code
  	2. > Validating  Message
  	3. > Validating Status 
     
8. ### Get the Student's Full Details
	>  Validation of the following field values in the test case :
	1. > Validating First Name
	2. > Validating Middle Name
	3. > Validating Last Name
	4. > Validating Date of Birth
	5. > Validating Language
	6. > Validating Year Of Experience
	7. > Validating Last Used Date
	8. > Validating House Number
	9. > Validating City
	10. > Validating State
	11. > Validating Country
	12. > Validating Std Code
	13. > Validating Mobile Number
	14. > Validating Current Address
  	15. > Validating Status code 


9. ### Delete Specific Student
	> Validation of status code and message in the test case :
	1. > Validating Status Code
  	2. > Validating  Message

## Newman Report Summary:
![Newman Report Summary](https://github.com/shafinrahman912/Student_Details_REST_API_Full_Project/assets/83553368/3dd0fcc4-5324-4bad-80ff-8a69079c4861)

![Newman Report Summary](https://github.com/shafinrahman912/Student_Details_REST_API_Full_Project/assets/83553368/b97491b2-1ef6-4edb-8859-0d0da7a633e0)





