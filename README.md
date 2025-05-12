🧠 Research Hive

**Research Hive** is a php-based web platform for researchers to collaborate, share papers, and engage in meaningful discussions.

  ![{2AF25A6A-DF73-4CBD-A25D-EA823F1CD480}](https://github.com/user-attachments/assets/ce5e9725-9ca2-456f-8b7b-3013f4386f5f)

  ![{DD790C32-8D4D-47B5-B775-97AE0737DBF2}](https://github.com/user-attachments/assets/19228ae9-73d6-45c0-ae4b-dec37f337e6b)

  ![{36432AEF-869D-4608-8D09-A5EF13CF0D7B}](https://github.com/user-attachments/assets/c9d5a2a7-835a-42bc-a8dd-222079073d2f)

  ![{3C7F2998-0495-4570-AE3C-CF0A596FDBE6}](https://github.com/user-attachments/assets/0766c926-efac-4888-a759-49b427573877)

  ![{EA9D3374-8632-4FB8-AA46-BE0E2F6F6174}](https://github.com/user-attachments/assets/bfd7825a-18d5-4998-8b59-5a7e94772c50)

  ![{F04AA6FD-E9DC-4D9A-B630-31D5A51A1278}](https://github.com/user-attachments/assets/e16adbdc-7378-4a6a-a503-0ed7c4c74738)

  ![{C5AD7A6F-179C-4834-B5B4-EC8CBAF62F07}](https://github.com/user-attachments/assets/084a2635-8591-406b-9f17-c167e0ddd43b)

  ![{C86F3C51-F7CE-43B5-BD51-15F2375C0085}](https://github.com/user-attachments/assets/4a38dd89-9ddb-4f6f-9a39-24a9fd6b8987)

  ![{1807D65E-F1B8-48BD-A6CA-E7F8C2C8BB45}](https://github.com/user-attachments/assets/a6995e1e-693c-4540-b649-aa9ef34a7f37)
  
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
