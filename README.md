AI Risk Dashboard

AI Risk Dashboard is an interactive web application designed to analyze user/system risk based on multiple factors such as login attempts, password strength, phishing activity, and malware detection. Leveraging AI, machine learning, and modern frontend technologies, the dashboard provides intuitive risk scoring, visualizations, and actionable insights for informed decision-making.A cybersecurity tool that analyzes system configurations, detects vulnerabilities and predicts risk levels using AI.  

Features

Multi-format File Support: Upload CSV, JSON, or YAML files for risk analysis.
AI-powered Risk Scoring: Calculates a risk score based on custom algorithms and AI models.
Interactive Data Visualization: Dynamic charts and graphs powered by Chart.js.
Real-time Feedback: Updates dashboards instantly as new data is uploaded.
User-friendly Interface: Built with React.js and Tailwind CSS for smooth interaction.

Technologies Used

Frontend:
React.js, Tailwind CSS, Chart.js
Backend / AI:
TensorFlow.js (AI Model)
Custom Risk Scoring Algorithm
File Parsing:
PapaParse (CSV), js-yaml (YAML), JSON

How It Works
The AI Risk Dashboard analyzes user/system risk by combining file parsing, AI-based risk scoring, and interactive visualization. Here’s the step-by-step workflow:
Data Upload
Users upload their data in CSV, JSON, or YAML format.
Example fields: UserID, LoginAttempts, PasswordStrength, PhishingClicks, MalwareDetected.
File Parsing
The app uses PapaParse for CSV, js-yaml for YAML, and native JSON parsing.
Uploaded data is converted into a JavaScript object/array for processing.
Risk Scoring Algorithm
A custom algorithm evaluates each user’s data to calculate a risk score.
Factors include:
Weak passwords
Multiple login attempts
Phishing clicks
Malware detection
Optionally, a TensorFlow.js AI model can enhance scoring using machine learning.
Data Processing
The application normalizes the data and computes risk levels (e.g., Low, Medium, High).
Missing values are handled gracefully to avoid errors.
Visualization
Risk scores and statistics are displayed using Chart.js.
Dynamic charts (bar, pie, line) allow users to analyze trends and compare user risks.
Real-Time Feedback
Any changes in uploaded data instantly update the dashboard.
Users can interact with charts for detailed analytics.

![AI Risk Dashboard Flow](https://github.com/MojeshReddy/AI-Powered-Risk-DashBoard/blob/main/Image.png)

