<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
<h1 align="center">Instagram Clone</h3>
  <p align="center">
    An Instagram clone implemented with server-side dynamic pages <br> (Client-side dyanmic pages coming soon!)
  </p>
  <p align="center">
    <strong>EECS 485</strong> <br> September 2024 - Present
  </p>
</div>

## Table of Contents

   * [About The Project](#about-the-project)
   * [Tools and Languages](#tools-and-languages)
   * [Features](#features)
   * [Website Pages](#website-pages)
      * [Index](#index)
      * [User Profile](#user-profile)
      * [Followers](#followers)
      * [Following](#following)
      * [Post](#post)
      * [Explore](#explore)
      * [Login](#login)
      * [Create](#create)
      * [Delete](#delete)
      * [Edit](#edit)
      * [Password](#password)
   * [Acknowledgments](#acknowledgments)


<!-- ABOUT THE PROJECT -->
## About The Project

<p align="center">
  A multi-user, interactive clone of Instagram that is currently implemented with server-side dynamic pages that features the ability to create, update, and delete users, posts, comments, and likes. As a whole, this project aims to imitate the same kinds of experiences found in the real Instagram appication (including most other social media applications as well), with a number of different pages that as a whole form a functioning and unified user experience.
</p>

## Tools and Languages
<!-- [![C++][cplusplus]][cplusplus-url] -->

[![Python][python]][python_url]
[![HTML][html]][html_url]
[![CSS][css]][css_url]
[![SQLite][sqlite]][sqlite_url]

[![Flask][flask]][flask_url]
[![AWS][aws]][aws_url]
[![Jinja][jinja]][jinja_url]
[![PyCharm][pycharm]][pycharm_url]


<!-- FEATURES -->
## Features

- [ ] Created a Flask application in a Python virtual environment in order to connect to database and rendered webpages
- [ ] Utilized SQLite to create, store, and edit information from users in a common database (ie. users, posts, comments, likes, and followers)
- [ ] Rendered website pages by using templates and their context using the Jinja2 library
- [ ] Used session cookies to read the username of the logged-in user
- [ ] Successfully deployed on an EC2 instance provided by Amazon Web Services (AWS)

## Website Pages

Each webpage has a unique set of features that fulfills a particular set of goals, similar to Instagram itself

## Index

<p align="center">
  <img width="364" alt="Screenshot 2024-09-25 at 19 02 49" src="https://github.com/user-attachments/assets/9fb256ac-1df3-489d-b4b9-5214a1a72089"><br>
</p>

<p align="center"> 
  Also called the <strong>Main Page</strong>, it displays all of the posts that exist within the SQL database at any given time along with information about the post itself (ie. the post's owner, their profile picture, etc.), comments, and the ability to delete one's own comments
</p>

## User Profile

<p align="center">
  <img width="757" alt="Screenshot 2024-09-25 at 19 06 08" src="https://github.com/user-attachments/assets/f8a6e154-fed2-4042-99f1-bc47db5fd08d"><br>
</p>

<p align="center"> 
  Displays information specific to this given user (including the number of posts they have posted, the number of followers, etc.) There are also links that deal with the user's account, all of the posts that the given user has previouly posted, and allows for the creation of a new post.
</p>

## Followers

<p align="center">
  <img width="375" alt="Screenshot 2024-09-25 at 19 11 07" src="https://github.com/user-attachments/assets/646a0e2f-ce60-41ee-82a8-7fced18d294e"><br>
</p>

<p align="center"> 
  Lists each person that is following a given user, including their username and profile picture, along with a button that allows the current logged-in user to follow/unfollow them
</p>

## Following

<p align="center">
  <img width="324" alt="Screenshot 2024-09-25 at 19 08 40" src="https://github.com/user-attachments/assets/60cb93d0-7759-4017-a03d-6b4e6119527e"><br>
</p>

<p align="center"> 
  Lists each person that a given user is following, including their username and profile picture, along with a button that allows the current logged-in user to follow/unfollow them
</p>

## Post

<p align="center">
  <img width="443" alt="Screenshot 2024-09-25 at 19 16 24" src="https://github.com/user-attachments/assets/324d411d-435b-4eb2-9a05-8483325a3cf7"><br>
</p>

<p align="center"> 
  Displays a given post and related information (ie. the post's owner, their profile picture, and the timestamp), its comments, as well as the ability to like/unlike the post and delete your own comment
</p>

## Explore

<p align="center">
  <img width="205" alt="Screenshot 2024-09-25 at 19 21 10" src="https://github.com/user-attachments/assets/bbb0c183-f8de-4afb-b302-64d4b1c57d48"><br>
</p>

<p align="center"> 
  Displays users that you are not currently follows and allows you to follow/unfollow them respectively
</p>

## Login

<p align="center">
  <img width="232" alt="Screenshot 2024-09-25 at 19 14 43" src="https://github.com/user-attachments/assets/e59ffe11-ef4a-4178-983b-912fa20bb3fa"><br>
</p>

<p align="center"> 
  Displays buttons that allow a user to login via their username and password
</p>

## Create

<p align="center">
  <img width="315" alt="Screenshot 2024-09-25 at 19 15 18" src="https://github.com/user-attachments/assets/7266d959-8940-415c-af02-5c0ccd9266b1"><br>
</p>


<p align="center"> 
  Allows for the creation of a new user with a specific username, password, and to upload a specific profile picture
</p>

## Delete

<p align="center">
  <img width="209" alt="Screenshot 2024-09-25 at 19 13 40" src="https://github.com/user-attachments/assets/4683ffd9-84a1-4538-acf0-3da1cb69325b"><br>
</p>

<p align="center"> 
  Allows the logged-in user to delete their own account, along with all information associated with them (any posts, comments, likes, and user information)
</p>

## Edit

*Currently working on this portion*
<p align="center">
  <img width="551" alt="Screenshot 2024-09-25 at 19 18 54" src="https://github.com/user-attachments/assets/bca856f2-e7a5-414c-bacc-4e00e98dd5b6"><br>
</p>

<p align="center"> 
  Allows the user to change their account by uploading a new profile picture, changing their current password, or deleting their account
</p>

## Password

<p align="center">
  <img width="306" alt="Screenshot 2024-09-25 at 19 12 46" src="https://github.com/user-attachments/assets/58cd5229-8934-45e0-a388-7543cbeb6225"><br>
</p>

<p align="center"> 
  Allows the user to change their password to a new one
</p>


## Acknowledgments

[EECS 485 Project 1 Description](https://eecs485staff.github.io/p1-insta485-static/) <br>
[EECS 485 Project 2 Description](https://eecs485staff.github.io/p2-insta485-serverside/)

<!-- MARKDOWN LINKS & IMAGES -->

[flask]: https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white
[flask_url]: https://flask.palletsprojects.com/en/3.0.x/

[aws]: https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white
[aws_url]: https://aws.amazon.com/

[pycharm]: https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green
[pycharm_url]: https://www.jetbrains.com/pycharm/

[python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[python_url]: https://www.python.org/

[jinja]: https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black
[jinja_url]: https://jinja.palletsprojects.com/en/3.1.x/

[github]: https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white
[github_url]: https://github.com/

[sqlite]: https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white
[sqlite_url]: https://www.sqlite.org/

[html]: https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white
[html_url]: https://www.w3.org/TR/2011/WD-html5-20110405/

[css]: https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white
[css_url]: https://developer.mozilla.org/en-US/docs/Web/CSS


