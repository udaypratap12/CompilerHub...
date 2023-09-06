

SimpleOJ is a simple online-judge by which user can add programming problems and solve them.
**Only supports C, C++, Python language.**


### What An User Can Do?
 - User can login in with google. Used PassportJS for auth.
 - Signed In user can add new Problem with custom testcase. He can also edit and delete the problem.
 - Any user can run his code in the problem page. Only signed in user can submit the code.
 - User can see if the problem verdit is accepted, wrong answer or TLE after submitting the code. 
 - User can see his previous submission in a particular problem. He can also download the codes.

### How do I Run C, C++, Python Code?
I used nodejs child-process to run c, c++ and python code in background.

### Technology Used
  - ReactJS for frontend
  - MongoDB for database
  - NodeJS (Express) for backend
  - PassportJS for auth.
  - Docker


### How to run it in local machine?
1. <a href="https://docs.docker.com/engine/install/">Install docker</a> if you don't have it installed in your machine.
2. Clone this repo.
3. Run the following command and you are good to go.
   ```
   docker-compose up

