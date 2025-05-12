🧠 Research Hive

**Research Hive** is a php-based web platform for researchers to collaborate, share papers, and engage in meaningful discussions.

## 🔍 Features

- 👤 **User Profiles**
  Create and manage researcher profiles with name, bio, institution, and research interests.

- 📚 **Research Paper Repository**
  Upload, tag, search, and manage your personal collection of research papers.

- 💬 **Forum Discussions**
  Create Ideas/issue post focused on specific topics or institutions for focused engagement with the community with the option to further discussions.

- 👥 **connections**  
  Be able to connect with other researchers and visit their repository and get Dashboard update form their repository.

- 🤝 **Connect with Researchers**
  Search and connect with researchers with username.

- **Profile-visit**
  User can visit other researcher profiles and can download their repository.
  ![{2AF25A6A-DF73-4CBD-A25D-EA823F1CD480}](https://github.com/user-attachments/assets/ce5e9725-9ca2-456f-8b7b-3013f4386f5f)


## 🔧 Installation
For Frontend:

1. Clone the repository:

2. install php in your os. https://www.youtube.com/watch?v=n04w2SzGr_U

3. Download and install Xammp.https://www.apachefriends.org/

4. clone the repo inside xammp-->htdocs [ex--C:\xampp\htdocs\ResearcherHive]

5. Open folder in Vscode. install required extension such[PHP Server by brapifra,PHP Intelephense by Ben Mewburn intelephense.com,live]

That's all for frontend Now just paste this link (or serve this project will also take you to the homepage)  http://localhost/ResearcherHive/home.php

FOR BACKEND:

1. open Xaamp and create a database any name make sure to change db_connect file to your database information such as...
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "ResearchHive_database";

2. paste the following sql query from the ResearchHive_database.sql

You're done for the BACKEND.
go to db_connect.php uncomment //echo "Connection successful"; now go to http://localhost/ResearcherHive/db_connect.php and if you see  "Connection successful" then your database is successfully connect you can uncomment this.

If all of this is done correctly you should be able to use the website.
