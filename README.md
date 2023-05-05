# PramataAssignment

### I am writing to provide you with instructions on how to run a locally cloned repository of a social media platform API, which I have developed.

To begin with, you need to clone the repository using the following command: `git clone https://github.com/mohdashiq18/PramataAssignment.git`. Once you have cloned the repository, you need to install all the required packages to run the code successfully.

After installing the required packages, you can run the code using the command: `npm run server`. The code will run locally on port 8080.

To use the API, you can make use of tools such as Thunder Client or Postman. You need to sign up by using the `localhost:8080/register` (POST) endpoint and providing details such as your name, email, and password. Please note that there is validation in place to ensure that the details entered are valid.

Once you have signed up, you can log in using the `localhost:8080/login` (POST) endpoint by providing your email and password. Please ensure that the email and password match the ones you provided during signup.

After logging in, you can post a story using the `localhost:8080/postfeed` (POST) endpoint. And, if you want to add a comment to a post, you can use the `localhost:8080/comment/id` (PATCH) endpoint and provide your comment.

I hope these instructions are helpful in running the social media platform API. Please let me know if you have any further queries or require any assistance.

