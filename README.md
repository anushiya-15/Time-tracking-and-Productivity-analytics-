#  Chrome Extension for Time Tracking and Productivity Analytics


*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ANUSHIYA R

*INTERN ID*: CT04DG3464

*DOMAIN*:FULL STACK DEVELOPMENT

*DURATION*: 4 WEEKS

*MENTOR*: MUZAMMIL

*DESCRIPTION*:



As part of my ongoing internship at CodTech IT Solution, under the domain of Full Stack Web Development, I completed Task 4: Chrome Extension for Time Tracking and Productivity Analytics. This project involved developing a fully functional browser extension that actively monitors a user’s browsing habits, tracks time spent on different websites, and delivers insightful productivity analytics.

The objective of this task was to build a browser-based tool that supports self-monitoring, time management, and user productivity improvements. The extension functions in the background while the user browses, captures usage data in real-time, and presents this information through intuitive dashboards, including charts and categorized reports.

🎯 Objective
The primary goal of the project was to create a Chrome Extension that would:

Track time spent on websites

Categorize websites as productive or unproductive

Visualize browsing data in the form of charts

Store user activity data persistently using a database

Help users evaluate and manage their digital productivity

This application is targeted toward users who want to reduce online distractions, manage their work/study time more effectively, and gain visibility into their online behavior.

🛠️ Technologies Used
The project integrates both frontend and backend technologies, reflecting a true full-stack approach:

Frontend: HTML, CSS, JavaScript

Browser Extension: Chrome Extension APIs, manifest configuration

Backend: Node.js and Express.js

Database: MongoDB using Mongoose

Data Visualization: Chart.js for displaying graphs and charts

NPM Packages: Used for running the server, database connections, and time-related utilities

🧩 Components of the Extension
🔹 1. Manifest File (manifest.json)
The manifest defines the structure and permissions of the Chrome Extension. It specifies the scripts to run in the background, permissions like tab access, and connection to content scripts and the popup.

🔹 2. Content Scripts
These scripts are injected into each tab the user visits. They detect the activity on websites, monitor time spent, and send messages back to the background script.

🔹 3. Background Script
The background service worker maintains active tracking of tab changes, manages timing calculations, and ensures communication between the content scripts and backend.

🔹 4. Popup Interface
The popup is what users see when they click on the extension icon. It displays:

A list of websites visited

Time spent on each site

Graphs showing productive vs. unproductive time

Summary of total daily usage

🔹 5. Backend Server (Node.js)
The server receives and processes the time tracking data, stores it in MongoDB, and sends the required data back to the frontend UI for display.

🔹 6. MongoDB Database
User tracking data is stored securely in the database. It includes details like:

Website URLs

Time durations

Date and session data

Productivity classification

💼 Features Implemented
✅ Real-time tracking of websites visited

⏱️ Accurate time calculation per website and session

📊 Visualization with bar and pie charts (powered by Chart.js)

📁 Data storage in MongoDB for historical analysis

🟢 Session activity logging (start and end times)

🚫 Categorization of websites as productive or unproductive

🔄 Updates on browser events like tab switch, idle detection

🧠 Insight into productivity patterns throughout the day

🎓 Learning Outcomes
This project helped me sharpen both technical and conceptual skills in the full-stack domain. Here's what I gained:

🧑‍💻 Technical Exposure
Developed a multi-layered Chrome extension with background, content, and popup scripts

Worked with message passing APIs between components

Managed state persistence using a backend database

Built REST APIs in Node.js for data handling

Used Chart.js to render dynamic productivity graphs

📚 Conceptual Understanding
Understood browser behavior in handling tabs and scripts

Practiced asynchronous programming and event handling

Learned about the Manifest V3 standard and Chrome extension security policies

Designed user-friendly interfaces inside the popup

Organized backend logic for scalability and clean data flow

🗂️ GitHub Repository
The source code is publicly available at:
🔗 https://github.com/anushiya-15/Time-tracking-and-Productivity-analytics-

The repository includes:

manifest.json: Chrome extension configuration

popup.html, popup.js, popup.css: User interface code

background.js: Core logic for session and tab monitoring

content.js: Site-level interaction tracking

server/app.js: Express server with MongoDB connections

models/: Schemas and database structure

public/: Chart.js graphs and static files

🧠 Practical Applications
This extension has meaningful uses for various users:

💼 Professionals: Monitor work productivity

🎓 Students: Reduce time on social media or distractions

📈 Freelancers: Optimize billing time and focus

👨‍🏫 Educators/Managers: Introduce digital wellness programs

📌 Conclusion
The Chrome Extension for Time Tracking and Productivity Analytics is a practical tool developed during my internship to apply full-stack development skills in a real-world project. It taught me how to build tools that run directly inside browsers and contribute positively to user habits.

By combining technologies like Node.js, MongoDB, JavaScript, and Chrome APIs, I was able to deliver a complete solution that accurately monitors, analyzes, and displays productivity data. This project not only improved my technical abilities but also gave me insights into how product-based features are developed from the ground up.

It represents a milestone in my full-stack journey with CodTech IT Solution, and stands as a strong portfolio piece demonstrating proficiency in building full-stack web and browser-integrated applications.


*OUTPUT*

<img width="1917" height="1013" alt="Image" src="https://github.com/user-attachments/assets/8824f564-5199-4f40-a081-6a4ef505d693" />
<img width="511" height="467" alt="Image" src="https://github.com/user-attachments/assets/7c91a87a-64b0-46d1-8925-c2130a1e18ed" />
