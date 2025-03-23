# 📝 MERN GitHub App


*A powerful MERN-based web application integrating GitHub API*

## 📖 About the Project  
The **MERN GitHub App** is a **full-stack web application** that allows users to **search for GitHub profiles, view repositories, and access detailed information**. This app leverages the **GitHub API** to fetch real-time data and provides an interactive UI for enhanced user experience.

## 🔥 Features  
✅ **Search GitHub Users** – Enter a username to fetch profile details  
✅ **View Repositories** – Display a list of public repositories  
✅ **View Repository Details** – Get information on stars, forks, and languages used  
✅ **Bookmark Profiles** – Save favorite profiles for quick access  

## ⚡ Major Challenges Faced  
### ❌ **Handling GitHub API Rate Limits**  
- **Issue:** Limited API calls without authentication.
- **Solution:** Implemented OAuth and API keys for increased request limits.

### ❌ **Efficient Data Fetching & Pagination**  
- **Issue:** Loading large amounts of repositories slowed performance.
- **Solution:** Implemented **pagination** and **lazy loading**.

### ❌ **Managing Bookmarks Without Database Load**  
- **Issue:** Storing user preferences efficiently.
- **Solution:** Used **localStorage** for quick access without extra database queries.

## 🛠️ Tech Stack  
### **Frontend:**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="50" alt="React.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="50" alt="JavaScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="50" alt="HTML5"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="50" alt="CSS3"/>
</p>

### **Backend:**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="50" alt="Node.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" height="50" alt="Express.js"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="50" alt="MongoDB"/>
</p>

### **API Integration:**
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="50" alt="GitHub API"/>
</p>

## 📷 Screenshots  
### 🔹 User Search Page  
![Search Screenshot](https://via.placeholder.com/800x400?text=Search+GitHub+Users)  

### 🔹 Profile Details  
![Profile Screenshot](https://via.placeholder.com/800x400?text=User+Profile+Details)  

### 🔹 Repositories List  
![Repos Screenshot](https://via.placeholder.com/800x400?text=Repositories+List)  

## 🚀 Installation & Setup  
### **Step 1: Clone the repository**  
```bash
 git clone https://github.com/KsM16/mern-github-app.git
 cd mern-github-app
```

### **Step 2: Backend Setup**  
```bash
 cd server
 npm install
 npm start
```

### **Step 3: Frontend Setup**  
```bash
 cd client
 npm install
 npm start
```

### **Step 4: Set Environment Variables**  
Create a `.env` file in the **server** directory and add:
```plaintext
GITHUB_API_KEY=your_github_api_key
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```



## 🤝 Contributing  
Contributions are welcome! To contribute:  
1. **Fork** the repository  
2. **Create** a feature branch: `git checkout -b feature-branch`  
3. **Commit** changes: `git commit -m "Add new feature"`  
4. **Push** to the branch: `git push origin feature-branch`  
5. **Submit** a Pull Request  

