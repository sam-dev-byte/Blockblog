# Blockblog

This python web-app was created to emulate a blog and the different user types available.
By: Gift kipkemboi

## Description
This web-app allows the user to view,comment and like blog posts.The admin can add/delete posts and delete comments.

## Setup/Installation Requirements
* Live site can be accessed from the following link https://blog-donald.herokuapp.com/
  Email: gmanses@gmail.com

### Known Bugs
there are no known bugs but if spotted ,notify me @ gmansesco@gmai.com

### Behaviour Driven Development
* The program should return all posts on the home page<br>
Given:All posts<br>
When: View is changed to home page<br>
Then: All Posts are displayed<br>

* One should receive an email when signing up,subscribing and when a post is made<br>
Given:A sign up/subscription/post feature<br>
When: Email is validated <br>
Then: Email is sent to the email registered with<br>

* The program should abstract data<br>
Given: A user's role is "User"<br>
When: User logs in<br>
Then: Admin features are not shown<br>

* Likes/Comments should be recorded and displayed to all the users<br>
Given:A like/comment option is given<br>
When: User likes/comments a pitch <br>
Then: The value is added to the number of likes/comments<br>


### Technologies Used
* Atom was the source code editor of choice.
* Git and Github were used as my local and online repositories respectively.
* Flask was used as the micro-framework
* Heroku was used in deploying the live site
* Gmail was used as the email sender


### Support and contact details
* Contact me through my email:GMANSESCO@GMAIL.COM@gmail.com
* The source code is also contained within the folder containing this ReadMe with comments on the code thus third-party support can be offered.

### License
MIT
