# Tech Blog

## Description

The tech blog app is a CMS style blog site that allows users store and share articles with others in the tech industry.  Users have the option to create, update or delete their own articles, or make comments on other's articles.  A secure login process is used to ensure comments and articles are credited to the correct user. 

The home site displays all the article titles and dates that they were created.  If you are logged in, clicking on any title will give more information including the author, complete articles and any associated comments with the ability to add new comments.  There are dashboard links and a logout link in the nav bar at the top of the screen.  The dashboard site shows all the articles that you have written and also the ability to add another article.  Clicking on any existing articles will allow you to either edit or remove it.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)

## Installation

In order to run the program locally, you can download or clone the program from my GitHub site. In the root directory of the program, ensure all packages are available by typing 'npm install' in the command line in the root directory. You will also have to MySQL which can be downloaded at [https://dev.mysql.com/downloads/mysql/](https://dev.mysql.com/downloads/mysql/) and create a file named .env with the following two lines:<br />
DB_USER='your-mysql-username'<br />
DB_PW='your-mysql-password'<br />

## Usage

The tech blog program can be used to share and read technical articles.  A live website can be found [here](https://kunkelkevin-tech-blog.herokuapp.com/).

Screenshot showing main site:<br />
![Main Screenshot](/img/Screenshot-main.png "Main site with article titles")

Screenshot showing a single article with additional information and form to add comments:<br />
![Single Post Screenshot](/img/Screenshot-single.png "Single post page")

Screenshot showing Dashboard page with option to add new articles:<br />
![Dashboard Screenshot](/img/Screenshot-dashboard.png "Dashboard site")


## Questions

The Tech Blog can be found on the following [GitHub page](https://github.com/kunkelkevin/tech-blog).<br />If you have any additional questions, you can email me at [kunkelkevin@yahoo.com](mailto:kunkelkevin@yahoo.com)
