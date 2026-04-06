# 🚀 AI Discovery Platform (Cogninest)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

A sleek, community-driven web application to discover, compare, and rank the latest Artificial Intelligence tools. Built with a Python backend, this platform allows users to vote on their favorite AI applications, switch themes seamlessly, and submit new tools to the directory.

---

## 🌐 Live Demo
Experience the platform directly in your browser:  
**👉 [Launch Cogninest / AI Discovery](https://cogninest.onrender.com/)**

> ⏳ **A quick heads-up on loading time:** This application is hosted on a free cloud instance. If the site hasn't been visited in a little while, it goes to "sleep" and may take about 50-60 seconds to wake up on your first click. Grab a quick sip of coffee while it loads—I promise the smooth UI is worth the wait! ✨

---

## 📸 Platform Tour

Here is a look at the platform's core interface and interactive features. 

### Fluid UI & Theme Toggling


https://github.com/user-attachments/assets/e932f795-dfdd-4999-b837-41c8c706e629




### Seamless Scrolling & Discovery

https://github.com/user-attachments/assets/aa89b591-322f-4639-9fcc-26f1b89c5dbf




### Interactive Community Dashboard
<img width="1440" height="692" alt="Screenshot 1447-10-16 at 12 14 47 AM" src="https://github.com/user-attachments/assets/4cdd41c1-16d8-4e34-8645-79e6257fd11e" />


---

## ✨ Key Features

* **Dynamic Theming:** Seamless, fluid toggle between Light and Dark modes.
* **Community Voting System:** Users can browse and upvote today's top AI tools (e.g., ChatGPT, Gemini, DeepSeek).
* **Tool Submission Portal:** A dedicated UI for users to submit new AI tools to the database.
* **Search & Filter:** Easily query the database to find specific AI tools by name or category.
* **Newsletter Integration:** Built-in subscription UI to capture user emails for weekly updates.
* User Authentication & Profiles: Allow users to create accounts, log in, and manage their profiles. This enables personalized experiences like tracking submitted tools and voting history.
* Trending & Analytics Dashboard: Display real-time insights such as most upvoted tools, fastest-growing AI apps, and category-wise trends to enhance discovery and engagement.

---

## 📂 Repository Structure

The project follows a standard Python web application architecture using lightweight JSON for data storage:

~~~text
📦 ai-tools-discovery-web
 ┣ 📂 static          # CSS stylesheets, JavaScript files, and image assets
 ┣ 📂 templates       # Frontend HTML files (Jinja2 templates)
 ┣ 📜 app.py          # Main application logic and routing
 ┣ 📜 tools.json      # JSON database storing AI tools and vote counts
 ┣ 📜 users.json      # JSON database for user authentication/data
 ┣ 📜 requirements.txt# Python package dependencies
 ┗ 📜 Procfile        # Deployment configuration for Heroku/Render hosting
~~~

---

## 💻 How to Run Locally

To run this platform on your own machine, ensure you have Python installed.

**1. Clone the repository**
~~~bash
git clone https://github.com/mohd-ayan-dev/ai-tools-discovery-web.git
cd ai-tools-discovery-web
~~~

**2. Install dependencies**
~~~bash
pip install -r requirements.txt
~~~

**3. Start the application**
~~~bash
python app.py
~~~
*The app will be served locally. Open your browser and navigate to `http://localhost:5000` (or the port specified in your terminal).*

---

## 👨‍💻 About the Developer
**Mohammed Ayan** *Architecting intelligent systems and scalable cross-platform experiences.*

🔗 [Connect with me on LinkedIn](https://linkedin.com/in/mohammed-ayan-94ab6a1b6)
