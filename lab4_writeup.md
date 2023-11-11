# Introduction:
### Lab 4
### 11/10/2023
### Colby Rodriguez
---
# Executive Summary:
This lab teaches us the basics of how we can create a RESTful API. Not only did we learn how to create the RESTful API, but also how to test the CRUD functions that are included in 4A. The reason why we want a RESTful API is because it provides an interface where we can set up any type of front end and get the same data from a mobile app to a website. 
---
# Design Overview:
At a high level overview of the lab we made RESTful API that was able to handle CRUD functions in order to update a NoSQL database with data that we are generating. The lab contained a couple of new aspects but at its core it was still a todo app, just instead of using any UI it is all put to our database through HTTP requests. 

The first thing that we did was we went into lab 4A creating the CRUD functions and making sure that we had the proper permissions, or the cookie that we needed, so that we could start to create new tasks and test through our api.test.js file. After we created the CRUD functions we went into the api.test.js file and we started to create the tests that would either pass or fail based off of the criteria that was given in the lab. We used the command  `npm run test` in order to test our API and make sure that everything was working 

In lab 4B we kicked it up a notch by creating our own API and making sure that it worked by using our test cases that we already wrote in lab 4A. The creation of a RESTful API is too long to be explain in a paragraph but suffice to say that it was hard. There are a lot of moving parts in an API and getting all of them to work was hard but rewarding in the end. 

---
# Questions:
1. Name and discuss at least two of the benefits of writing unit tests before writing code.

__Answer:__ When we write unit tests before writing code its gives us much more room to test our code and make sure that its working. It also allows us to know that are tests are working as expected before. 

2. What would be some of the benefits of automating your test scripts (i.e. so they run at each commit)?

__Answer:__ It would be a lot easier to catch any errors that happen in the code and say that we are a SAAS company than we can make sure that we dont push anything that will break 

3. How long did this lab take you?

__Answer:__ Around 6-8 hours 

4. List three advantages to using a web API.

__Answer:__ One advantage of using an API is that i can take those results and put different front ends in front of it and have the same data be there. 
Another advantage is that when you are using a web API you are able to actually scale your application much faster because there is much better resource allocation. 
The last thing that is an advantage is versioning and maintaince for APIS. Since you can version it typically can help make sure that your API is always up and it ensures backwards compatibility. 

5. What are the differences between these four HTTP methods: GET, POST, PUT, and DELETE? Which ones are idempotent?

__Answer:__
GET, PUT, AND DELETE are idempotent
GET is used to pull data from a specified resource.
POST is used to submit data to be processed by a specific resource. Often times POST also creates a resource
PUT is used to update a resource. It can also create a new resource if there isnt a resource to update with the specific URI 
DELETE is used to delete a resource. 

---
# Lessons Learned:
__Work with People__

This lab really stretched me in every way possible and so i learned to work with people and especially to check my syntax with the people that are around me because on lab 4B I spent around 8 hrs trying to fix really stupid syntax issues.

__Routing__

Learning how to route things was super important for me because i have never made anything like this and so learning these routing techniques really helped me realize how APIS work and it gave me a new appreciation for them. 

__Make Great Test Cases__

Learning how to make test cases with Jest and the implementation of them in our lab really helped me troubleshoot the issues that i was having in lab 4b because i was able to see where my requests were failing and i was able to change those trouble points in my lab. 

---
# Conclusion:

* Implement CRUD functionality with a RESTful API 
* Learned how to write tests using the Jest framework 
* learned how to route requests
* Implementing node and actually using it in my terminal to make sure it worked.
* Learned how to use the TA's more efficiently 
* Learned how to use mongoDB. 
---