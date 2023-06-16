<br />
<div align="center">
  <a href="" target="_blank">
    <img src="https://nova-practicing.herokuapp.com/static/media/logo-removebg-preview.b0a2d844156f54942b53.png" width="200" height="80" alt="Logo" >
  </a>

  <p align="center">
    Website to Help developers practice and pass interviews with the help of our professional interviewers.
  </p>
    <a href="https://nova-practicing.herokuapp.com/"> Demo</a>
    ·
    <a href="https://www.figma.com/file/n7Lg3oVdi980NcbIwHl5xi/Nova?node-id=0%3A1">Figma Design</a>
</div>

<div align="center">

<br/>
<br/>

</div>

<br>

## 🔹About Nova

<table>
<tr>
<td>

**Nova**, a website dedicated to assisting users in practicing interviews with the best and most experienced interviewers.
</td>
</tr>
</table>


# 🔹User Stories


🔸**Story 1:** <sup>(Feature 1: User Authentication)</sup>
As an new user, I want to be able to easily sign up for an account, so that i can access Nova's mock interview services.

**Tasks:**
1. Add a sign-up button to the navigation bar of the site.
2. Develop a sign-up page for new users.
3. Integrate social media APIs to allow users to login via their social media accounts.
4. Implement a secure authentication system for interviewee accounts.
5. Develop a user dashboard that allows registered users to manage their account settings and access mock interviews.
6. Conduct user testing and feedback collection to optimize the sign-up process.

**Success criteria::**
1. The sign-up form should be easy to use and require minimal information from the user.
2. The social media APIs should be succesfully integrated.
3. The authentication system should be secure and protect user data.
4. The user dashboard should be easy to navigate and provide clear access to mock interviews.
5. The sign-up process should have a high completion rate and low drop-off rate.


---

🔸**Story 2:** <sup>(Feature 14: Email Verification)</sup>
As a new user, I want to receive a verification email after signing up, so I can confirm my email address and start using Nova's services.

**Tasks:**
1. Implement email verification system
2. Send verification email to user after sign up
3. Verify user's email address when they click on verification link

**Success criteria:**
1. User receives verification email after signing up
2. User's email address is confirmed and they can access Nova's services after clicking on verification link

---

🔸**Story 3:** <sup>(Feature 11: Personalization)</sup>
As a registered user, I want to be able to view my profile information, such as my name, email, and interview history, so I can keep track of my progress.

**Tasks:**
1. Create user profile page
2. Display user's basic information (name, email) on the profile page
3. Display user's interview history on the profile page

Success criteria:

1. User can access their profile page from the dashboard
2. User's basic information is displayed accurately on the profile page
3. User's interview history is displayed accurately on the profile page

---

🔸**Story 4:** <sup>(Feature 11: Personalization)</sup>
As a registered user, I want to be able to update my profile information, so I can keep my details accurate and up-to-date.

**Tasks:**
1. Add form to user profile page to allow updating of basic information
2. Implement update functionality for basic information
3. Add form to user profile page to allow updating of password
4. Implement update functionality for password

**Success criteria:**
1. User can access update forms for basic information and password from their profile page
2. User can update their basic information and password using the forms
3. User's updated information and password are saved correctly in the database

---

🔸**Story 5:** <sup>(Feature 11: Personalization)</sup>
As a registered user, I want to view my upcoming mock interviews so that I can prepare accordingly.

**Tasks:**
1.  Add a page or section to the user interface where registered users can view their upcoming mock interviews.
2.  Implement the functionality to display the relevant data from the database, including the date and time of the interview and the technology being covered.

**Success criteria:**
1.  The page or section should be easy to access from the user's account dashboard.
2.  The data displayed should be accurate and up-to-date.
3.  The user should be able to prepare for their upcoming mock interviews based on the information provided.

---

🔸**Story 6:** <sup>(Features 15, 16: Zoom Integration)</sup>
As a registered user, I want to join a mock interview through a Zoom link so that I can do the interview.

**Tasks:**
1.  Integrate Zoom API into Nova's system.
2.  Allow users to select a mock interview from the available options.
3.  Generate a unique Zoom link for each mock interview session.
4.  Send the Zoom link to the user via email or provide it in the user's account page.
5.  Allow users to join the Zoom meeting directly from the Nova website or by clicking the link provided in the email.

**Success criteria:**
1.  Zoom API is successfully integrated into Nova's system and functional.
2.  Users can select a mock interview from the available options and request to join.
3.  Each mock interview session has a unique Zoom link generated.
4.  Users receive the Zoom link via email or can access it in their account page.
5.  Users can successfully join the Zoom meeting from the Nova website or by clicking the link provided in the email.

---

🔸**Story 7:**
As a registered user, I want to cancel a mock interview if I'm unable to attend so that I can free up the time slot for others.

**Tasks:**
1.  Provide a feature for registered users to cancel their mock interviews.
2.  Free up the time slot in the system and notify the interviewer.

**Success criteria:**
1.  Registered users can cancel their mock interviews.
2.  The system updates and notifies the interviewer of the cancellation.

---

🔸**Story 8:** <sup>(Feature 6: Security)</sup>
As a registered user, I want to be able to log out of my account so that my account remains secure.

**Tasks:**
1.  Implement a "Log Out" button on every page of the website.
2.  Clear the user's session when they log out.

**Success criteria:**
1. Users are able to log out of their account from any page.
2. The user's session is cleared upon logging out.

---

🔸**Story 9:** <sup>(Feature 1: User Authentication)</sup>
As an interviewee, I want to be able to log in to my account, so I can browse available mock interview options.

**Tasks:**
1. Implement login system
2. Create interviewee dashboard that displays available mock interviews
3. Allow interviewee to select and schedule a mock interview

Success criteria:

1. Interviewee can log in to their account using their email and password
2. Interviewee is presented with a dashboard that displays available mock interviews
3. Interviewee can select and schedule a mock interview from the dashboard

---

🔸**Story 10:** <sup>(Feature 11: Personalization)</sup>
As an interviewee, I want to be able to view my past mock interviews, including the interviewer's feedback and my performance, so I can learn from my mistakes and improve my skills.

**Tasks:**
1. Create mock interview history page
2. Display interviewee's past mock interviews on the history page, including feedback and performance
3. Allow the interviewee to filter mock interviews by technology or difficulty level

**Success criteria:**
1. interviewee can access their mock interview history page from the dashboard
2. interviewee's past mock interviews are displayed accurately on the history page, including feedback and performance
3. interviewee can filter mock interviews by technology or difficulty level and see accurate results

---

🔸**Story 11:**
As an interviewee, I want to be able to browse and select mock interviews based on specific technologies, such as JavaScript or Python, so I can focus on improving my skills in areas that interest me.

**Tasks:**
1. Implement search and filter functionality for mock interviews
2. Allow interviewee to search and filter mock interviews by technology, difficulty level, and other relevant criteria
3. Display search and filter results accurately on the mock interview dashboard

**Success criteria:**
1. interviewee can access the mock interview dashboard from the dashboard
2. interviewee can search and filter mock interviews by technology, difficulty level, and other relevant criteria
3. Mock interview dashboard displays accurate search and filter results

---

🔸**Story 12:** <sup>(Feature 11: Personalization)</sup>
As an interviewee, I want to be able to choose the difficulty level of my mock interview, such as easy, intermediate, or advanced, so I can challenge myself and improve my skills accordingly.

**Tasks:**
1.  Add the option to select the difficulty level of a mock interview to the user interface.
2.  Implement the functionality to filter mock interviews by difficulty level based on the interviewee selection.
3.  Store the difficulty level of the mock interview in the database.

**Success criteria:**
1.  The interviewee should be able to easily select the difficulty level of their mock interview from the user interface.
2.  The mock interview options should be filtered and displayed based on the interviewee's selected difficulty level.
3.  The selected difficulty level should be stored and associated with the mock interview.

---

🔸**Story 13:**
As an interviewee, I want to view my mock interview feedback/reviews so that I can see how I performed.

**Tasks:**
1.  Design a feature that allows interviewees to save their mock interview feedback/reviews.
2.  Implement a "Save" button on the mock interview feedback/review page.
3.  Create a database to store the saved feedback/reviews.
4.  Test the feature to ensure that saved feedback/reviews can be accessed and viewed by the interviewee.

**Success Criteria:**
1. Interviewee can save mock interview feedback/reviews.
2. Interviewee can access saved feedback/reviews at any time.
3. Saved feedback/reviews are stored securely and can only be accessed by the user who saved them.
4. Interviewee can delete saved feedback/reviews if they no longer need them.

---

🔸**Story 14:**
As an interviewer, I want to be able to view my upcoming and past mock interviews, so I can keep track of my schedule and performance.

**Tasks:**
1.  Implement a page or section where interviewers can view their upcoming and past mock interviews.
2.  Populate the page or section with the relevant data from the database, including the interviewee's name, the date and time of the interview, and the technology being covered.

**Success criteria:**
1.  The page or section should be easy to access from the interviewer's account dashboard.
2.  The page or section should display all relevant information about the interviewer's past and upcoming mock interviews.
3.  The page or section should be regularly updated and accurate.

---

🔸**Story 15:**
As an interviewer, I want to be able to provide feedback to interviewees after a mock interview, so they can learn from their mistakes and improve their skills.

**Tasks:**
1.  Add a feature to the user interface where interviewers can submit feedback for a completed mock interview.
2.  Implement the functionality to store the feedback in the database and associate it with the relevant mock interview.
3.  Notify the interviewee when feedback has been provided.

**Success criteria:**
1.  The feedback submission process should be intuitive and easy to use for interviewers.
2.  The feedback should be stored accurately and associated with the relevant mock interview.
3.  The interviewee should be notified in a timely manner when feedback is available.

---

🔸**Story 16:**
As an interviewer, I want to be able to view my feedback history and the interviewee's progress, so I can see how my feedback has helped them improve over time.

**Tasks:**
1.  Add a page or section to the user interface where interviewers can view their feedback history and the progress of interviewees they've worked with.
2.  Implement the functionality to display the relevant data from the database, including the interviewee's name, the date and time of the interview, and the feedback provided.

**Success criteria:**
1.  The page or section should be easy to access from the interviewer's account dashboard.
2.  The data displayed should be accurate and up-to-date.
3.  The feedback history and progress of interviewees should be displayed in a clear and organized manner.

---

🔸**Story 17:**
As an admin, I want to have access to a list of all registered Nova users so that I can view an overview of the user base.

**Tasks:**

1. Implement a "View All Users" page accessible only to admins.
2. Retrieve all registered Nova users from the database.
3. Display user information such as username, email, and registration date on the "View All Users" page.
4. Add filtering options to the page to allow admins to filter users by registration date or username.
5. Add pagination to the page to improve its performance.

**Success Criteria:**
1. Admins can access the "View All Users" page and view the list of all registered Nova users.
2. User information including username, email, and registration date are displayed on the page.
3. Filtering options are available to allow admins to filter users by registration date or username.
4. Pagination is implemented to improve the page's performance when displaying a large number of users.

---

🔸**Story 18:**
As an admin, I want to be able to view all pending interviewer applications so that I can review them and decide whether to approve or reject them.

**Tasks:**
1. Implement a "View Pending Interviewer Applications" page accessible only to admins.
2. Retrieve all pending interviewer applications from the database.
3. Display applicant information such as name, email, and application date on the "View Pending Interviewer Applications" page.
4. Add options to approve or reject the applications on the same page.
5. Implement backend code to handle the approval or rejection of the applications and update the database accordingly.
6. Send an email notification to the applicant upon approval or rejection of the application.

**Success criteria:**
1. Admins can access the "View Pending Interviewer Applications" page and view all pending interviewer applications.
2. Applicant information including name, email, and application date are displayed on the page.
3. Admins can approve or reject the applications on the same page.
4. The database is updated accordingly upon approval or rejection of the application.
5. The applicant is notified via email upon approval or rejection of the application.

---

<br>
    
## 🔹 Database Schema


<img src="https://cdn.discordapp.com/attachments/967089710566625310/980948829723578448/unknown.png"/>
          
    
## 🔹Installation
  1. clone Nova repo
  ```
  https://github.com/waseem-alfarram/Mock-Interviews-Website.git
  ```
  2. install npm packages in server folder
  ```
  npm install
  ```
  3. install npm packages in client folder
  ```
  cd client
  npm install
  ```
  4. write env variables in .env file 
  ```
DEV_DATABASE_URL=mongodb://localhost:27017/nova
TEST_DATABASE_URL=mongodb://localhost:27017/test-nova
JWT_SECRET='<your secret key>'
API_KEY='<your API key>'
API_SECRET='<your secret key>'
EMAIl='<your email>'
EMAIL_PASSWORD='<your password>'
  ```
  <br>


## 🔹Contributors
* [Waseem Alfarram](https://github.com/waseem-alfarram)
* [Mahmoud Alhato](https://github.com/Mahmoud-Ahmad2)
* [Osama Alnahhal](https://github.com/Osama-M-AlNahhal)
* [Omar Abu Rabie](https://github.com/omaraburabie3)
* [Amran Almasri](https://github.com/AmranElmasri)
