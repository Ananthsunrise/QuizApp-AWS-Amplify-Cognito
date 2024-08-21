# QuizApp-AWS-Amplify-Cognito

In this project, We created a quiz app by hosting a web page in aws amplify. In this user need to register and login their details and practice the questions.


AWS services used:  
AWS Amplify
AWS Cognito
AWS IAM


Procedure :  
1.First we need to setup enviroment. Open your vs code editor or any ide which have installed with node.js on it.

2.Need to install amplify cli and configure amplify on vs code editor. You can get commands from this repo --> amplify-cognito-quiz

3.after installing above, we need to give our IAM login credentials which the user must have policy for adminstratoracessamplify.

4.install react app (backend) on vs code and host it on amplify. you can get commands from the file which was attached in this repo.

5.We need to give login facilty for users by using cognito. execute thease commands -> amplify add auth amplify push. 
  copy app.js file code from github tho paste in app.js file in vs code editor. then run thease commands - -> npm install @aws-amplify/ui-react  npm start
  
6.Now we need to add functionality and styling for quiz. for that you need to copy quiz.js and quizdata.ja files from github and paste it on vs code edithor under src folder.

7.Now we need to push our code from vs code editor to github by creating new repo in github. vreate ne repo in github and execute attched commands to push the code from local to github.

8.finally we need to host a frontend in amplify. go to amplify- click host a webapp-click github-select repo-save and deploy.
