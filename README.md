# Social Media Analysis using SQL
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
</head>
<body>

<h2>About Project</h2>
<ul>
  <li>This project focuses on the EDA of social media data using SQL. It was executed on Google Colab using SQLite.</li>
  <li>It involves the creation of a database and answering questions based on the data. This database stores user profile information, connections, and engagement features.</li>
  <li>We can leverage this data to understand the audience, identify influencers, and implement suitable marketing strategies.</li>
</ul>

<h2>About Database</h2>
<ul>
  <li>The database consists of tables like:</li>
  <li>Posts: Details user-generated posts, including post ID, user ID (linked to Users table), content, and posting date.</li>
  <li>Comments: Records user comments on posts, with comment ID, post ID (linked to Posts table), user ID (linked to Users table), text, and posting date.</li>
  <li>Likes: Tracks user likes on posts, featuring like ID, post ID (linked to Posts table), user ID (linked to Users table), and like date.</li>
  <li>Users: Stores vital user information like user ID, username, email, and join date.</li>
  <li>Followers: Manages user following relationships, including follower ID, follower user ID (linked to Users table), following user ID (linked to Users table), and date of follow.</li>
</ul>

</body>
</html>
