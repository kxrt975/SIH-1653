# Smart India Hackathon Workshop
# Date: 13/3/2025
## Register Number:212224110029
## Name:Karthik padmanaban R
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea

1. Centralized Hub: i) A web and mobile platform where alumni can register, interact, and contribute, ensuring accessibility and convenience.
ii) Provide a one-stop solution for networking, donations, events, and career opportunities.

2. Networking Opportunities: i) Introduce AI-driven connection suggestions based on alumni profiles, such as location, industry, and shared
interests. ii) Create dedicated forums for discussions, mentorship, and collaboration.

3. Career Support: i) Build a job and internship portal for alumni to post opportunities and for students/alumni to apply. ii) Enable mentorship
programs, pairing students with experienced alumni.

4. Philanthropy Simplified: i) Design a transparent donation portal that shows where contributions are allocated (e.g., scholarships, events,
infrastructure). ii) Allow alumni to donate directly from their mobile wallets or online payment systems.

5. Community Engagement: i) Use gamification: Reward active alumni with badges, points, or leaderboard positions to encourage
participation. ii) Launch regular events and reunions with easy RSVP management and feedback forms.

6. Recognition and Pride: i) Highlight alumni success stories on the platform to inspire both current students and peers. ii) Integrate a feature
to let alumni showcase their professional achievements or projects.

7. Feedback Channels: i) Use real-time surveys or polls to understand alumni needs and gather improvement suggestions

## Proposed Solution / Architecture Diagram

![image](https://github.com/user-attachments/assets/6b2a6db3-e945-4bb3-97be-3e7c6b53830b)


## Use Cases

![image](https://github.com/user-attachments/assets/468475e0-6d70-4141-8e00-134473ad0ab1)


## Technology Stack

Front-End: React.js (Web), Flutter (Mobile App) for cross-platform compatibility.

Back-End: Node.js with Express.js.

Database: PostgreSQL for relational data and MongoDB for unstructured data like alumni success stories.

Payment Gateway: Razorpay/PayPal.

Hosting: AWS/GCP for scalability and reliability.

Security: i) Data encryption (SSL/TLS). ii) OAuth2 for secure user authentication. iii) Role-based access control (RBAC) for sensitive admin
operations


## Dependencies

Front-End: React.js (Web), Flutter (Mobile).

Back-End: Node.js (Express.js), PostgreSQL, MongoDB.

Authentication: OAuth2, JWT, SSL/TLS.

Payments: Razorpay or PayPal API.

Hosting: AWS/GCP, Firebase (optional for notifications).

Real-Time Features: Socket.io (chat), Chart.js (analytics).

Notifications: Twilio/SendGrid (SMS/Email).

CI/CD: GitHub Actions or Jenkins, Docker.

Testing: Jest, Postman, Selenium.

Analytics: Google Analytics, Mixpanel.

This stack ensures scalability, security, and a seamless user experience.

