# Productivity Chrome Extension with ReactJS

NAME : PALLAVI MHAISKAR

INTERN ID : CT08JTR

DOMAIN : FRONT END DEVELOPMENT

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

DESCRIPTION :

I developed a Chrome Extension using React.js that helps users track their time spent on websites. The extension monitors the number of seconds and minutes a user spends on a particular website. Once the predefined time limit is exceeded, it displays a warning to notify the user. This extension is useful for productivity management, reducing screen time, and controlling excessive browsing.

Objective of the Chrome Extension
The main goal of this Chrome extension is to:
✅ Track time spent on individual websites in real-time.
✅ Set a predefined time limit for different websites.
✅ Show a warning message when the limit is exceeded.
✅ Help users manage their screen time and improve productivity.

This extension is ideal for users who want to reduce distractions, manage online time effectively, or set limits for kids or employees.

Technologies Used
1. React.js
React.js was used to build the frontend popup UI, making it interactive and easy to use.

2. Chrome Extension API
The Chrome Storage API and Chrome Tabs API were used to track website activity and store user data.

3. JavaScript (ES6+)
Modern JavaScript features such as async/await, promises, and ES6 syntax improved performance and readability.

4. Manifest v3
The extension is built using Manifest Version 3 (MV3), which enhances security and performance.

5. Bootstrap & CSS
Bootstrap and CSS were used to create a clean and responsive UI.

Features of the Chrome Extension
1. Real-Time Website Tracking
The extension monitors how long a user spends on a particular website and updates the data in real-time.

2. Customizable Time Limits
Users can set a time limit for specific websites (e.g., 30 minutes for YouTube).

3. Warning Notification
When the user exceeds the limit, a popup warning appears, alerting them to stop browsing.

4. Persistent Data Storage
The extension remembers the time spent even after the browser is closed using Chrome Storage API.

5. Simple and Intuitive UI
The extension provides a clean and easy-to-use popup where users can check their website usage and adjust settings.

Development Process
1. Setting Up the Chrome Extension
The project was structured with:

Manifest.json → Configures permissions and background scripts.
Background.js → Tracks active tabs and time spent.
Content.js → Injects scripts to monitor page activity.
Popup (React UI) → Displays time spent and settings.
2. Implementing Time Tracking
Used Chrome Tabs API to detect when a user opens a website and track time spent using setInterval.

3. Managing State in React
Used useState and useEffect hooks to store and display website usage statistics.

4. Warning System Implementation
When the time exceeds the user-defined limit, a Chrome notification is triggered.

5. Testing & Deployment
Tested the extension across multiple websites and browsers.
Packaged and installed the extension manually in Chrome Developer Mode.

Conclusion
Building this Chrome Extension with React.js and Chrome APIs enhanced my knowledge of browser extensions, event-driven programming, and time management solutions. The extension provides an efficient way to track online time, helping users stay productive and control screen time.

This project demonstrates how React.js and Chrome APIs can be combined to create useful productivity tools! 🚀

![Image](https://github.com/user-attachments/assets/853157a0-cbcc-4822-9481-ffe0b8a48afc)
  
