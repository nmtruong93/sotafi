# sotafi
This project for sotafi

# Guide to deploy in heroku app
Open terminal and type:
1. heroku login
2. heroku apps: create <your-app>
3. cd <your-project>
4. touch index.php
5. Open file index.php to add this code: 
   ```php
   <code><?php include 'index.html';?>
   ```
6. git init
7. git add .
8. git commit -m "your-comment"
9. git push heroku master
