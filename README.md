🌐 JD’s Cloud Full Stack Deployment using Ansible
This project is a real-world demonstration of how you can deploy a complete full-stack web application on AWS using Ansible automation. The project separates the application into three different layers — Frontend, Backend, and Database — each hosted on its own EC2 instance. Everything is provisioned and configured automatically using Ansible playbooks, which makes it a production-style project with DevOps practices.

🔧 How the Project Works — Step by Step
Three EC2 instances are launched:

One each for frontend, backend, and database.

Each instance is listed in an Ansible inventory file (hosts.ini).

A main playbook (site.yml) is run from the Ansible controller to configure all layers.

Each component is automated using its own playbook:

frontend.yml: Installs Nginx and deploys a beautiful HTML+CSS page.

backend.yml: Installs Node.js, clones a GitHub app, and runs it.

database.yml: Installs MariaDB, creates a database and user, and configures access.

✅ What’s Special About This Project?
🔁 Fully Automated: Just one command deploys the whole app.

🌍 Cloud-Based: Uses AWS EC2 to simulate real-world deployment.

📂 Structured: Clean folder structure, clear roles, and readable code.

💡 Educational: Great for learning Ansible, Linux, cloud, and DevOps all at once.

🎨 Visually Clean UI: Includes a stylish frontend that confirms all services are working.

🧾 Technologies Used
Ansible – for automation

AWS EC2 – cloud infrastructure

Nginx – frontend server

Node.js + Express – backend logic

MariaDB – database

HTML + CSS – user interface

🎯 Final Result
Once deployed, visit your frontend server's public IP in a browser. You’ll see:

🚀 JD's Full Stack App Deployed with Ansible!
Everything is working perfectly 🎯
✅ Frontend | ✅ Backend | ✅ Database

Screenshots:


<img width="1918" height="1019" alt="final output" src="https://github.com/user-attachments/assets/f412a10a-d459-4841-942b-352d5d286cd0" />

<img width="1919" height="1079" alt="wsl 1" src="https://github.com/user-attachments/assets/b4b7114c-991f-4178-9f12-1d3076985d1d" />

<img width="1918" height="966" alt="wsl 2" src="https://github.com/user-attachments/assets/6d9dcb25-9928-4a86-910f-b98e446cd77b" />

<img width="1920" height="1080" alt="nginx" src="https://github.com/user-attachments/assets/b0c6bdd7-f20f-4080-bd5e-3009459645d6" />

<img width="1920" height="1080" alt="ec2-servers" src="https://github.com/user-attachments/assets/89ba7287-4ebd-4321-ab67-426140c8e00f" />

<img width="1916" height="886" alt="about" src="https://github.com/user-attachments/assets/767f011e-e9c1-40e8-ab97-4fe9eae4c905" />


👨‍💻 Author
Devanand Jayaraman (JD)
https://github.com/DEVANAND-JAYARAMAN

📄 License
This project is open source and available under the MIT License.


