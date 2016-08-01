# StudentSurvey_RESTful
RESTful web services and prime faces

This is an extension of the application developed as StudebtSurvey_JSF2. 
Here I have re-implemented everything using PrimeFaces UI library.
This includes using the look and feel of default theme of PrimeFaces. 
In addition, I have developed a RESTful web services that returns city and state given a zipcode.
An asynchronous call to the RESTful web service should be used to automatically populate city and state based on zipcode entered by the user.
I have limited the following zipcode, city, and state combination for implementation and testing.
zip: 22312, city: Alexandria, state: VA
zip: 22030, city: Fairfax, state: VA
zip: 22301, city: Tysons Corner, state: MD
zip: 20148, city: Ashburn, state: VA
The homepage of the application will have menu with links 
1) Student Survey, which allows a prospective student to fill out a survey form, and 
2) List All Surveys, which allows a user to view all surveys done to date.
An additional text box called Raffle is provided. 
The user will be asked to enter at least ten comma separated numbers ranging from 1 through 100 in the Raffle field.
This information will be used to announce whether the student wins a free movie ticket by computing the standard deviation. 
The information is stored on Oracle 10g running on the George Mason servers. 
This application is a dynamic web project and is deployed on Tomcat. 
The Amazon EC2 with a Tomcat application server was used to deploy the war file.

URL: http://ec2-54-174-153-59.compute-1.amazonaws.com:8080/SWE645_Homework3/
