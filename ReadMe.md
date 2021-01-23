# Lesson 2 Practice Hands-On

# Directions

For your Lesson 2 Practice Hands-On, you will be practicing what you have learned about HTTP verbs. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page.

Setup
Open up your terminal/command prompt.

Navigate to your desktop in your terminal:

cd Desktop
Then, navigate to the Express-Course directory in your terminal:

cd Express-Course
Requirements
Step 1
To begin, generate a new project (within the Express-Course directory) using the Express/Handlebar generator.

Call this app L02HandsOn
Don't forget to run npm install
Install and run Nodemon
Step 2
Create an array that is named flowers and includes the following elements:

Orchid
Iris
Hydrangea
Amaryllis
Dahlia
Daffodil
Bleeding Heart
Step 3
In the get method, check to see and respond accordingly that if you have a certain flower, send back a message saying "Yes, we have [flower] in our garden" and if you don't, respond, "Nope, we do not have [flower] in our garden, but maybe we should plant it!"

Hint! Use .includes().

Step 4
Create a post method that will add a flower that is not in the array into it and will respond, "We already have that flower, no need to add it" if it already exists in the array.

Step 5
Use Postman to check and see that these are returning the correct messages based on the HTTP verb.
