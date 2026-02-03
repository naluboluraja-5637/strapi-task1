This project describe how to

-> Create a Strapi application
-> Run it locally
-> Manage the project using Git & GitHub
-> Work with multiple branches (main & develop)
-> Create a Pull Request without directly touching the main branch

########### 🛠️ Prerequisites ###############
-> At first install the Node.js in our laptop
-> Git

🚀 Step 1: Create Strapi Application:
npm create strapi-app@latest my-strapi-app -- --quickstart --skip-cloud

--quickstart → Uses SQLite and auto-configures Strapi
--skip-cloud → Skips Strapi Cloud login

▶️ Step 2: Run Strapi Application
Go into the project directory:
cd my-strapi-app
  Run the app:
npm run develop

🌐 Step 3: Access Strapi Dashboard
Open your browser and visit:
http://localhost:1337/admin
Create your admin user when prompted.
🌿 Git Workflow (Very Important)
🔹 Branch Strategy
main → Stable / production-ready code
develop → All development work happens here

❌ Never push directly to main
🔧 Step 4: Initialize Git Repository
Inside the project root:
git init
git add .
git commit -m "Initial Strapi project setup"

🌱 Step 5: Create Develop Branch
git branch develop
git checkout develop

☁️ Step 6: Connect to GitHub Repository
Add your GitHub repo as remote:
git remote add origin https://github.com/naluboluraja-5637/strapi-task1.git

⬆️ Step 7: Push Branches to GitHub
Push main branch:

git checkout main
git push -u origin main

Push develop branch:

git checkout develop
git push -u origin develop

Output Images:

<img width="1920" height="1080" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/724d0534-4592-4db3-9a96-3cac19810486" />

<img width="1920" height="1080" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/a980ec0f-df9f-4684-8f36-33a45ce8b293" />

<img width="1920" height="1080" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/613a00aa-c148-4030-927f-e0dbd1ad2d8b" />

<img width="1920" height="1080" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/c5068636-832f-4104-b95d-fe571888e8dd" />
