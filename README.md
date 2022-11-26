# YES!+_webapp
API calls used in this website
---------------
A. **User**  
1. /add_user -  
Adding new user to database		  
Returns a JSON object { "status":number }

2. /login -   
Logging in an already existing user - Returns a JSON object { "status":number, "userdata": { "email": user_email, "type": user_type } }  
If the user doesnt exist	          - Returns a	JSON object { "status":number, "userdata": null }  


B. **Event**   
1. /add_event	-   
Adding a new event to database		  
Returns a JSON object { "status":number }  

2. /display_event -   
Displaying all the events from the database  
Returns a JSON array [ { event object }, { next event object }, ... ]  


C. **Testimonial**   
1. /add_testimonial -   
Adding a new testimonial to database	  
Returns a JSON object { "status":number }  

2. /display_testimonial -   
Displaying all the events from the database  
Returns a JSON array [ { event object }, { next event object }, ... ]  


Click here to see the website : https://bityesplus.web.app/




