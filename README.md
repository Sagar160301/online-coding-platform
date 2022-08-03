# Getting Started

1. `git clone https://github.com/masai-codes/online-coding-platform.git`
2. `cd online-coding-platform`
3. `npm install`
4. Check [.env](.env) file to add current paths.
5. `npm start`

# Schema

- [Problem](./server/features/problem/problem.gql)
- [Submission](./server/features/submission/submissions.gql)
- [User](./server/features/user/users.gql)
- [Group](./server/features/group/groups.gql)
- [Assignment](./server/features/assignment/assignments.gql)

# Tutorial

## Admin

**HOW TO BEGIN TO CREATE A PROBLEM**

1. Sign in on the platform using your credentials. Make sure you're an admin.
2. After signing in, go to _PROBLEMS_ tab, which is in the Main Menu. It should redirect you to problems page where all problems should be listed.
3. Click on _Create New Problem_ button.
4. Add a problem title, it will help you to find your problem.
5. Add a Boilerplate URL, "which is a GitHub repository URL in which the boilerplate code is present. Make sure your the problem repository is public as well as it should be usable as template. (You can check repository settings to convert your repository into a template.)
6. After pasting the URL, the platform will fetch the readme from the problem repository. If you're not able to see the description, then:
   - Does `README.md` file contain some text?
   - Is the problem repository public?
   - Is the URL of the repository is correctly pasted.
   - If all these are checks are done, please connect with admin lohit@masaischool.com
7. Choose a difficulty level according to your problem. It can be easy (or) medium (or) hard.
8. In the Tag section you can choose multiple programming languages based on your problem and boilerplate.
9. Click the button Create it will create a new problem on the platform. You should be able to see the new problem in the _Problems_ section.

**HOW TO CREATE AN ASSIGNMENT**

1. Sign in on the platform using your credentials. Make sure you're an admin.
2. After Signing in, go to _Assignments_ tab, which is in the Main Menu. It should redirect you to Assignments page where all Assignemnts should be listed.
3. Click on _Create New Assignment_ button.
4. Add a Assignment Name, which will help you to find your assignment.
5. Select a Group. That will indicates, which group will get access of this assignment,
6. Select Start Date and Time, when the assignement will start (or) users will get access of this assigemnt for solving.
7. Select End Date and Time, when the assignment will end (or) users will not access this assignment after that time.
8. Add description/message in the description box. The message/description which you want to share with users about this assignment.
9. Select problems for Assignment:

    - choose problems from listed Problems table.
      (or)
    - If the problem is not avilable, then create a new problem by following the _Create Problem_ procedure.

10. Click the button Create it will create a new Assignment on the platform. You should be able to see the new assignment in the _Assignments_ section.

## User

**HOW TO SOLVE AN ASSIGNMENT**

1. Sign in on the platform using your credentials. You will be redirected to the _Assignments_ page, where all assignments are listed.
2. Click one of the assignments, which you want to solve. You will be redirected to assignment view page, where you can see the list of problems of that assignments and also the details of that assignment.
3. Click on any one problem, you will be redirected to the problem solving page. On left side you can see the problem details and description.
4. Fork the repository (or you can download a zip, unzip in your own repo, use your own repo. The repo needs to be part of `masai-course` or the repo needs to be public), the repository link is avilable in the problem description and start solving the problem.
5. After solving the problem, submit your _Github URL_ and _Deployment URL_. Click the submit button.
6. After submit check your submission details in the _MySubmissons_ section. To check the status of your submission click the _Refresh_ button. It will update the status of your submission.
7. After Evaluation of your code, the score will updated on the Mysubmission table based on your submission and you can also see your Best Score of that problem.
8. After the score will updated, click on Option and then click View Option. It should redirect to a new page where you can see the logs of your submission.
9. Follow the procedure from 3 to 8 for solving the rest of problems of that assignment.
