BUILDING SERVERLESS REGISTRATION WEBAPP

STEP - CREATE registration form using html, css,js

STEP1 - Create DynamoBD 
		    table name - registration_table
			  partition key - email
			  explore item

STEP2 - Create IAM role for LMABDA
        IAM role name = RegistrationFormRole
			  permission: 
		1- CloudWatchFullAccess
		2-AmazonDynamoDBFullAccess

STEP3 - Create Lambda Function
			  Function name - registration-form-function
			  Runtime - Python 3.10
        Add role in lambda function
        Deploy the code

STEP 4- create API GateWay
			rest API
			API name = registrationAPI
			create resource
				Enable API Gateway CORS
			create method 
			    post method
			    enter lambda name
			    *enable cors
			DEPLOY API


		  
         

			

