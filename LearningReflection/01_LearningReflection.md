# TODO

> Please use the below questions as guidelines to help you think and plan your Learning Reflection Report

## 1. How was your experience testing the given Webapp?

- The project testing assignment was surprisingly enjoyable. Although the whole course content was fairly interesting (this is my first encounter with Software Testing), I imagined writing test cases to be a more tedious and repetitive job. However, I was positively surprised at how engaging the testing process was. To write good test cases, one needs to perform actual testing, imagine different scenarios, and actively think of situations in which the app may fail. The app we tested was a good fit in the sense that it is user friendly but, at times, not that easy to navigate, especially considering the lack of previous experience with the app, which added a dose of excitement when figuring out how everything works (for example, it took me a few minutes to figure out how to delete projects and issues).

## 2. How did you write or manage your test case? Describe the process?

- Before starting to write test cases, I carefully reviewed the Login page, which was already pre filled with all important information and examples of positive and negative test cases. I decided to complete the assignments in the same order a user would normally interact with the app: first the Registration page, then the Project page, and finally the Issue page.

- The next step was filling in information about Documentation, Pre and Post Conditions, and Tags, and defining some basic variables. Then, I visited the web page I was testing and interacted with it in different ways. I tried using different credentials, different data formats, and also leaving some fields empty. I tested different combinations and took notes on how the system behaved each time I changed the inputs. For example, when testing the Registration page, I noticed that the Username cannot be duplicated, and that it cannot be too short. I also discovered that it can contain “-” or “\_” characters, despite the instructions telling the user to enter only alphanumeric characters.

- Each time I tried a new scenario, I added any variable needed to complete those steps. At the beginning, I hard coded some of the inputs, but later realized that adding a few more variables was a cleaner approach, as it reduced the number of registration credentials I needed to create. After I successfully logged in using valid credentials, I also noticed that some of them could not be reused, so I created alternative credentials in the form of variables.

- For the Projects page, I repeated the same process. When trying different combinations of inputs, I observed how the system behaved in each situation. Every time I tested a new scenario, I wrote a test case for it using the appropriate variables. However, sometimes certain variables could not be reused, so I created new ones. All of this was done to make the test execution process more straightforward. One interesting realization was that it is possible to create a blank project with a previously used name, as long as the project group (or namespace) is not exactly the same as the one used by the previously created project with that name.

- Writing test cases for the Issue page was the easiest of the three pages, since the process for successfully creating an Issue requires only an Issue name. The name is always valid regardless of length or the use of spaces, special characters or numbers. Because other configuration steps can be skipped (and there were many), I did not list them separately as I did for the Registration or Project pages. The only invalid step is leaving the Issue name empty, so I created a negative test case for that scenario.

## 3. Do you recommend any other tools or styles for Test case management.

- As a complete beginner in software testing, I have not personally used any other tools for testing, so the current setup seems more than enough as a starting point. However, in the future I would like to use a tool like Jira. I already have some experience with Jira for project management purposes, but I have never used it specifically for software testing. It would be interesting to see how test management works inside Jira and how it compares to the setup we used in this course.

## 4. Which IDE (Visual Code or Atom or else) have you used to edit files?

- I have only used Visual Studio Code so far. Since this is the tool I have used in many different projects, I am fairly familiar with its functionality and comfortable using it. I also have my Visual Studio Code connected to my GitHub account, which makes synchronizing the local and remote repositories much easier.

## 5. Did you find any trouble? how did you solve the trouble?

- Despite this project being an enjoyable experience, I did encounter some challenges. For example, I was unsure how to display valid credentials for the Registration page. At first, I created fake email address and username (with the proper format), since the teacher also used "XYZ" as a username. Then I consulted with my teammates, who suggested adding my real credentials but hiding sensitive information, such as email or password. I found this approach to be clearer, as I could then use my personal account for later testing of the Project and Issue pages.

- Another issue I encountered was difficulty navigating some parts of the GitLab app. Although the app is fairly easy to use, I initially had trouble finding the delete option for both projects and issues, but I eventually managed to locate it and create test cases based on the steps.

- Finally, despite being present during the Project introduction lesson, watching the video again, and studying the materials, I was at times confused about how detailed my test cases needed to be. For that reason, I added some comments (particularly in the Registration page) to explain certain circumstances. Additionally, this was my first time creating test suites, so I was not always sure if I was going in the right direction when including some of the details. Hopefully, I managed to explain everything clearly and write useful test cases.

## 6. Did you find any trouble using Github? have you used Github before? where?

- I have used GitHub a lot in various school projects and although I am not yet fully comfortable with some of the more advanced commands, I am confident using it for basic functionalities, such as creating repositories, pushing and pulling, cloning repositories locally, linking a local repository to a remote one (or unlinking them), and using both the Terminal and Visual Studio Code interfaces. I had never used GitHub prior to my studies at Laurea, but so far, I have used it in almost all of my technical courses (Web Design, Programming with Python and JavaScript, Mobile App Design and Development, etc.). I did not encounter any trouble using it for this course.

## 7. If in the future if you need to automate these test cases, which framework or language will you use? and describe why (Robot Framework, Cypress, Selenium, or any other )

- If in the future I need to automate these test cases, I would like to use Selenium with either Python or JavaScript, since I feel most comfortable with those two languages. I think this combination is beginner-friendly, and there are many learning resources available. Selenium allows testing web applications by simulating how a real user interacts with the browser, which is in a way similar to the manual testing we did in this project.

## 8. Kindly search the term `Tester` `Automation Tester` glassdoor and LinkedIn or any other job search website. Currently, list the skills and competencies that are most in-demand in software testing

- Here are some of the skills I encountered:
  - Programming in diferent languages (Java, Python, JavaScript, TypeScript etc.)
  - Use of automation tools (Selenium, Cypress)
  - Familiarity with SDLC, Agile or DevOps workflows, CI/CD, version control
  - Bug reporting and test management tools (Jira, TestRail)
  - Analytical thinking and problem-solving
  - Attention to detail
  - Communication and collaboration

## 9. **Let's assume** that if you are going to continue with the career in Software Testing, which technical and soft skills do you need to fill up the blank in your resume?

- If I were to continue a career in Software Testing, I believe my strengths would be attention to detail and effective communication with teammates, although there is always room for improvement. On the technical side, however, I feel I am still lacking crucial skills and would like to develop more. Specifically, I want to gain experience with test automation tools and frameworks such as Selenium, Cypress, or Robot Framework, learn more about managing test data, and improve my ability to write clear and good quality test cases. I would also like to become more familiar with test management tools like Jira. I believe that strengthening these technical skills, combined with my existing soft skills, would help me become a well rounded and efficient software tester.

## 10. Write short Learning Reflection and Free words Do you think that project helped in putting theoretical knowledge into practice? Describe? (is there anything else that you would like to share with us concerning the current study module). e.g. regarding the quality of content and your learning (or) improvement ideas?

- I would say that this project was very helpful in putting theoretical knowledge into practice, and moreover, in strengthening that knowledge. While we had examples of how test cases should look, writing them ourselves was a completely different experience, as one learns best by doing things practically.
  I really liked the study material and how the course was designed and implemented. It followed logically organized sections that built upon previous knowledge. Additionally, the material was versatile, since we could use the book or watch videos, which also had transcripts available. As someone who prefers reading to listening when studying, I really appreciate this. One recommendation for improvement would be to include more projects like this one, perhaps one additional project or several smaller lab works, as this is a great way to learn and improve practical skills.
