# ise-tech-exercise
UNO Fall 2018
Intro to Software Engineering: Tech Exercise Source Code

This is the source code for the Tech Exercise(s) for the University of Nebraska at Omaha's CSCI 4830: Intro to Software Engineering class.

Based on Amazon AWS's Node.js / DynamoDB tutorial: https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/nodejs-dynamodb-tutorial.html

Main URL: http://techex.ddns.net/

# Uses
1. Node.js on Amazon Linux
2. jQuery
3. Bootstrap CSS
4. DynamoDB
5. AWS EC2 Elastic Beanstalk

# How it works
* First the page load the HTML to show the inputs for the to-do list, namely the item, "due date", and any web link the user might want.
* Clicking the add button adds the info to a DynamoDB table (called "todo-items")
* The "Get To Dos" button retrieves the list of To Do items from the database (well, it's supposed to - can't seem to get it working).
