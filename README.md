💼 AI Finance Advisor
AI Finance Advisor is a web-based personal finance tool that provides interactive modules for budget planning, investment growth calculation, loan payment estimation, and an AI-powered financial advisor chatbot. It includes user authentication (login/register) using browser local storage.

🔧 Features
👤 User Authentication: Register and login securely with localStorage-based credential storage.

📊 Budget Planner: Input income and expenses to analyze total spending, savings rate, and get tailored financial advice.

📈 Investment Calculator: Visualize future investment value based on principal, monthly contributions, interest rate, and time.

🏠 Loan Calculator: Estimate monthly payments, total interest, and total repayment based on loan parameters.

🤖 AI Advisor Chatbot: Ask financial questions and get smart AI-generated responses on budgeting, investing, saving, debt, and more.

🖥️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (Vanilla)

Storage: Local Storage (for user data)

UI Design: Responsive, clean design using modern CSS features like grid, flexbox, and gradient backgrounds

AI Chatbot: Rule-based response generator implemented in JavaScript

🚀 How to Run
Download or Clone Repository

bash
Copy
Edit
git clone https://github.com/yourusername/ai-finance-advisor.git
Open in Browser
Simply open financer_advicer.html in any modern web browser (Chrome, Edge, Firefox).

📸 Screenshots


🔐 Login Details (Default)
You can log in using the following default credentials:

bash
Copy
Edit
Username: user
Password: password
Or register your own account using the "Sign Up" form. All data is stored locally in the browser's storage.


🤖 AI Chatbot Examples
"How should I manage my budget?" → Recommends the 50/30/20 rule

"What is a good investment plan?" → Suggests diversification and long-term strategies

"How do I save for emergencies?" → Recommends building a 3–6 month emergency fund


📁 Project Structure
graphql
Copy
Edit
ai-finance-advisor/
│
├── financer_advicer.html   # Main single HTML file (includes CSS & JS)
└── README.md               # Project documentation


📌 Notes
This project is frontend-only. No backend server or database is used.

User accounts and session states are stored in browser localStorage.

For production use, consider securing authentication and storing user data in a backend sy
