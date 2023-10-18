# alx-backend-storage
📃 Topics Covered.
MySQL advanced.
🔧 Project setup.
## Install MySQL 5.7 in ubuntu

# Add key to server
sudo apt-key add signature.key

# Add apt repo
sudo sh -c 'echo "deb http://repo.mysql.com/apt/ubuntu bionic mysql-5.7" >> /etc/apt/sources.list.d/mysql.list'

sudo apt-get update

# Check mysql available versions
sudo apt-cache policy mysql-server

# Install mysql 5.7
sudo apt install -f mysql-client=5.7* mysql-community-server=5.7* mysql-server=5.7*

# Check if installed
mysql --version


# Create project directory and readme.
mkdir ./alx-backend-storage/
touch ./alx-backend-storage/README.md

cd alx-backend-storage

# Create git repository.
git init
git add .
git commit -m 'first commit'
git remote add origin <REMOTE_URL>
git push
💻 Projects
0x00. MySQL advanced
🔧 Project setup.
# Create project directory and readme.
mkdir ./0x00-MySQL_Advanced/
touch ./0x00-MySQL_Advanced/README.md
cd 0x00-MySQL_Advanced
👉 Go to project

0. We are all unique!
Write a SQL script that creates a table users following these requirements:

With these attributes:
id, integer, never null, auto increment and primary key
email, string (255 characters), never null and unique
name, string (255 characters)
If the table already exists, your script should not fail
Your script can be executed on any database
Context: Make an attribute unique directly in the table schema will enforced your business rules and avoid bugs in your application


🔧 Project setup.
# Create project directory and readme.
mkdir ./0-uniq_users.sql/
touch ./0-uniq_users.sql/README.md
cd 0-uniq_users.sql
👉 Go to project

0x02. Python - Async Comprehension

0x02. Python - Async Comprehension
Type Annotation (Strongly Dynamically typed) in python. Reason for implementing type Annotation:

Code documentation.
Linting and validation.
🔧 Project setup.and arrangement
# Create project directory and readme.
mkdir ./0x02-python_async_comprehension/
touch ./0x02-python_async_comprehension/README.md
cd 0x02-python_async_comprehension
👉 Go to project

👨 Author and Credits.
This project was done by SE. Kelvin Agimogim. Feel free to get intouch with me;

📱 WhatsApp +2348063641215

📧 Email kelvinagimogim@gmail.com

👍 A lot of thanks to ALX-Africa Software Engineering program for the project requirements.
