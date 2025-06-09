# project5

java --version

chrome
jenkins.io
download

left side 
generic java package .war
download  karne ke baad uska path copy karna

C:\Users\lavan\Downloads


java -jar C:\Users\lavan\Downloads\jenkins.war --httpPort=8080     9090     9191



copy password

chrome meh jake 
http://localhost:8080

http://localhost:9090


paste password


install suggested plugins

after loading


getting started

username: lavz
password: ew22ic23
confirm password:

fullname: lavz g
e-mail address: ur mail id


save and continue




save and finish


start using jenkins

dashboard open hoga



in windows





CHANDANA

[12:42, 06/06/2025] Chandana K L: cat /etc/os-release
[12:42, 06/06/2025] Chandana K L: java --version
[12:42, 06/06/2025] Chandana K L: sudo wget -O /etc/apt/keyrings/jenkins-keyring.asc \
[12:42, 06/06/2025] Chandana K L: echo "deb [signed-by=/etc/apt/keyrings/jenkins-keyring.asc]" \
[12:42, 06/06/2025] Chandana K L: sudo apt-get update
[12:42, 06/06/2025] Chandana K L: sudo apt-get install jenkins
[12:42, 06/06/2025] Chandana K L: sudo systemctl start jenkins
[12:42, 06/06/2025] Chandana K L: sudo systemctl status jenkins


CA  Experiment 5 - Introduction to Jenkins: What is Jenkins?,
Installing Jenkins on Local or Cloud Environment, Configuring
Jenkins for First Use
Experiment 5: Introduction to Jenkins
🌟 Objective
To understand the fundamentals of Jenkins, install it on a local or cloud environment, and configure it for first-time
use.
🔹 1. What is Jenkins?
Jenkins is an open-source automation server used for: ✅ Continuous Integration CI – Automatically testing and integrating code changes ✅ Continuous Deployment CD – Automating application deployment
✅ Building Pipelines – Managing end-to-end software development workflows ✅ Plugin-Based Extensibility – Supporting tools like Maven, Gradle, Ansible, Docker, and Azure DevOps
🚀 Why Use Jenkins?
✔ Automates builds and tests
✔ Reduces manual intervention
✔ Improves software quality
✔ Works with multiple tools and platforms
🔹 2. Installing Jenkins
Jenkins can be installed using multiple methods: 󾠮 Windows Installer (.msi) – Recommended for Windows 󾠯 Linux Package Manager – Best for Linux Users 󾠰 Jenkins WAR File – Universal method using Java
Weʼll cover all three approaches.
🟢 2.1 Prerequisites
🔹 Java 11 or 17 is required for Jenkins.
Check Java version:
If Java is not installed, download it from:
Download the Latest Java LTS Free
1 java -version
2
98
Coders Arcade ──────────────────────────── DevOps Lab Manual
©2025 Coders Arcade V2.0 📺 www.youtube.com/c/codersarcade  Saurav Sarkar
🟠 2.2 Installing Jenkins on Windows MSI Installer) – Recommended
✅ Step 1: Download Jenkins
🔗 Download from: Download and deploy
Choose Windows Installer (.msi) for an easy setup.
✅ Step 2: Install Jenkins
󾠮 Run the downloaded .msi file. 󾠯 Follow the installation wizard. 󾠰 Select Run Jenkins as a Windows Service (recommended). 󾠱 Choose the installation directory (default: C:\Program Files\Jenkins ). 󾠲 Click Install and wait for the setup to complete.
✅ Step 3: Start Jenkins
󾠮 Open Services ( services.msc ) and ensure Jenkins is running. 󾠯 Open a web browser and go to:
✅ Step 4: Unlock Jenkins
󾠮 Find the initial Admin Password in:
󾠯 Copy the password and paste it into the Jenkins setup page.
✅ Step 5: Install Recommended Plugins
Jenkins will prompt you to install plugins. Click "Install Suggested Plugins".
✅ Step 6: Create Admin User
󾠮 Set up a Username, Password, and Email. 󾠯 Click Save and Finish.
🔹 Jenkins is now ready! 🎉
Access it anytime at:
🟢 2.3 Installing Jenkins on Linux Ubuntu/Debian)
✅ Step 1: Add Jenkins Repository
✅ Step 2: Install Jenkins
1 http://localhost:8080
2
1 C:\Program Files\Jenkins\secrets\initialAdminPassword
2
1 http://localhost:8080
2
1 wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
2 sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ >
/etc/apt/sources.list.d/jenkins.list'
3
1 sudo apt update
99
Coders Arcade ──────────────────────────── DevOps Lab Manual
©2025 Coders Arcade V2.0 📺 www.youtube.com/c/codersarcade  Saurav Sarkar
✅ Step 3: Start Jenkins
✅ Step 4: Access Jenkins
Find the initial password in:
Then open Jenkins in a browser:
🟠 2.4 Installing Jenkins Using WAR File Works on Any OS
This method allows you to run Jenkins without installing it as a service.
✅ Step 1: Download the Jenkins WAR File
🔗 Download from: Download and deploy
Choose Generic Java Package (.war).
✅ Step 2: Run Jenkins Using Java
Navigate to the folder where the .war file is downloaded and run:
🔹 This will start Jenkins on port 8080.
✅ Step 3: Open Jenkins in Browser
Go to:
✅ Step 4: Unlock Jenkins & Setup
Follow the same steps as the Windows/Linux installation:
✔ Find the initial password
✔ Install plugins
✔ Create an admin user
🔹 Jenkins is now running without installation!
To stop Jenkins, press CTRL  C in the terminal.
2 sudo apt install jenkins -y
3
1 sudo systemctl start jenkins
2 sudo systemctl enable jenkins
3
1 sudo cat /var/lib/jenkins/secrets/initialAdminPassword
2
1 http://localhost:8080
2
1 java -jar jenkins.war --httpPort=8080
2
1 http://localhost:8080
2
100
Coders Arcade ──────────────────────────── DevOps Lab Manual
©2025 Coders Arcade V2.0 📺 www.youtube.com/c/codersarcade  Saurav Sarkar
🔹 3. Configuring Jenkins for First Use
✅ 3.1 Understanding the Jenkins Dashboard
After logging in, you will see: 🔹 New Item → Create Jobs/Pipelines 🔹 Manage Jenkins → Configure System, Users, and Plugins 🔹 Build History → View previous builds 🔹 Credentials → Store secure authentication details
✅ 3.2 Installing Additional Plugins
Jenkins supports plugins for various tools like Maven, Gradle, Docker, and Azure DevOps.
🔹 To install a plugin: 󾠮 Go to Manage Jenkins → Manage Plugins 󾠯 Search for the required plugin 󾠰 Click Install without Restart
✅ 3.3 Setting Up Global Tool Configuration
Configure Java, Maven, and Gradle in Jenkins: 󾠮 Go to Manage Jenkins → Global Tool Configuration 󾠯 Add paths for:
JDK ( C:\Program Files\Java\jdk-17 )
Maven ( C:\Maven\apache-maven-<version> )
Gradle ( C:\Gradle\gradle-<version> )
󾠰 Click Save
