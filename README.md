In this coursework, you will build a simple social networking website for people who like music. The
requirements for the social network are as follows:

1. Each user will be able to register an account with a username and password
2. A user should be able to login and see their home page (see below)
3. A user will be able to create a profile when they register, which will consist of:
• A person’s name
• An avatar picture (this can be a URL to an image hosting service such as imgur)
• A list of favourite music genres (chosen from a drop-down menu)
4. A user should be able to post messages on their timeline – a message may contain a link
5. When posts are created and added to a timeline, sections of the post that are hyperlinks (i.e., of
the form “http://…..” should be turned into clickable hyperlinks). A more advanced form of this
requirement is to detect links to images (URLs ending in ‘,jpg’, ‘.png, or ‘.gif’) and display them
using ‘<img />’ tags in the post when it is displayed on a timeline.
6. Users should be able to search for other people by music genres
7. When presented with a list of users (as a result of a search), users should see a button they can
click to ‘follow’ that user (if they already follow that person, the ‘follow’ button should not be
displayed. Clicking on a user’s name should display that user’s public home page.
8. A user should see on their timeline posts from users they follow, as well as their own posts.
9. A user should be able to see a page of people they follow and who follow them. Note that a user
who is following you and who you also follow is a ‘friend’.
10. The user’s home page should contain user profile information and the user’s timeline of posts
(their posts and posts of people they follow), as well as links to pages that display followers and
followed users. The home page should also display the form for creating new posts.
11. Each user should also have a public home page, which can be seen by any user – this should
display profile information and a timeline of that user’s posts only (and not of the people they
follow). The timeline should be in descending date/time order
Your application MUST be written using PHP and CodeIgniter, and follow MVC guidelines. Data must
be stored in a MySQL database. Not using PHP and CodeIgniter will result in an invalid submission.
jQuery/AJAX is not required for this coursework, and using jQuery/AJAX will not result in additional
marks. The coursework MUST work and be deployed on the university web server and MySQL
database (this is to allow remote testing and evaluation). Applications deployed on personal machines
will NOT be accepted. It is recommended (but not essential) that you use the bootstrap CSS framework
for CSS layout andappearance. Also, you may findthe bootstrap iconsetuseful increating navigational
schemes in your website.
With respect to appearance, please make sure your image sizes do not impact the page layout.
