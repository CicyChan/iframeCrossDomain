### iframeCrossDomain

This demoe is for passing the message beween to different domains

Here is the steps 

1. create two different workspace in Eclipse  , and add the the tomcat server

2. create dynamic web probject in two workspace 

3. copy the index.html to one project . Child.html to another project 

3. adjust the tomcat server port to 7080 in the Eclipse workpace which include project that inclucde the indix.html

4. adjust the tomcat server port to 9080 in the Eclipse workpace which include project that inclucde the Child.html

5. add below host infomaiton to the host file , and the locaiton is C:\Windows\System32\drivers\etc

	127.0.0.1       localhost
	127.0.0.1       ChildHost

6. Run the applicaotns in tomcat server

7. run the index.html , then you can communicate the message beow two different domains

