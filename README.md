<h1>💸 FinTrack++ – Advanced C++ Personal Finance Manager</h1>

<p>
FinTrack++ is a command-line based personal finance and investment tracking system developed in modern <b>C++</b>. It empowers users to manage their <b>income</b>, <b>expenses</b>, <b>investments</b>, and <b>financial goals</b> efficiently. The project is backed by a secure <b>SQLite3 database</b> and makes use of <b>OpenSSL</b> for password encryption, ensuring both data integrity and security.
</p>

<p>
It’s designed to solve real-world financial challenges faced by individuals, especially students and working professionals who want to gain control over their finances without relying on complex or paid tools. The system is ideal for <b>internship portfolios</b>, <b>job-ready development</b>, and practical application in MNC environments.
</p>

<hr>

<h2>🌍 Real-World Problem It Solves</h2>
<p>
In today’s fast-paced world, many people struggle with:
</p>
<ul>
  <li>Lack of awareness about their financial habits</li>
  <li>Failure to track daily expenses and earnings</li>
  <li>No clarity on investments and financial goals</li>
  <li>Over-spending due to poor budget discipline</li>
</ul>

<p>
<b>FinTrack++</b> solves these problems by:
</p>
<ul>
  <li>Providing a <b>secure financial dashboard</b></li>
  <li>Tracking every rupee spent or earned with historical logs</li>
  <li>Offering investment simulation for planning the future</li>
  <li>Guiding users to set and meet goals with progress tracking</li>
  <li>Exporting data in CSV/JSON for future visualization or backup</li>
</ul>

<hr>

<h2>🔧 Features</h2>

<h3>🛡️ User Management</h3>
<ul>
  <li>Signup/Login with <b>SHA-256 encrypted</b> passwords</li>
  <li>Personalized dashboard per user</li>
</ul>

<h3>🧾 Expense & Income Tracking</h3>
<ul>
  <li>Categorized tracking: Food, Transport, Education, etc.</li>
  <li>Date-wise history with undo functionality</li>
  <li>Support for Wallet, Bank, Credit Card accounts</li>
</ul>

<h3>💰 Investment Module</h3>
<ul>
  <li>Track <b>Stocks, Mutual Funds, FDs, Crypto</b></li>
  <li>SIP & Compound Interest calculators</li>
  <li>Simulate ROI & visualize financial growth</li>
</ul>

<h3>🏁 Financial Goals</h3>
<ul>
  <li>Create and track goals like "Buy a laptop in 6 months"</li>
  <li>Get alerts as you reach key milestones</li>
</ul>

<h3>📊 Budgeting & Analytics</h3>
<ul>
  <li>Set monthly limits per category</li>
  <li>Get alerts when approaching or crossing budgets</li>
  <li>Export data as CSV/JSON for visualization in Python, Excel, etc.</li>
</ul>

<h3>🧠 AI-Based Insights (Coming Soon!)</h3>
<ul>
  <li>Predict overspending trends</li>
  <li>Recommend ideal investments based on behavior</li>
</ul>

<hr>

<h2>📁 Folder & File Structure</h2>

<pre>
FinTrackPlusPlus/
│
├── src/                         # All source (.cpp) files
│   ├── main.cpp
│   ├── auth.cpp
│   ├── db.cpp
│   ├── transactions.cpp
│   ├── investments.cpp
│   ├── goals.cpp
│   ├── analytics.cpp
│   └── utils.cpp
│
├── include/                     # Header files
│   ├── auth.h
│   ├── db.h
│   ├── transactions.h
│   ├── investments.h
│   ├── goals.h
│   ├── analytics.h
│   └── utils.h
│
├── database/                    # SQLite DB initialization & scripts
│   ├── schema.sql
│   └── data_sample.sql
│
├── assets/                      # Optional: graphs, charts, images
│
├── README.md                    # ✨ Main documentation
├── Makefile                     # Build automation (or CMakeLists.txt)
├── LICENSE                      # Your preferred license
└── .gitignore                   # Ignore build files, DB, etc.
</pre>

<hr>

<h2>🧪 Technologies Used</h2>
<ul>
  <li><b>C++17</b> with Object-Oriented Design</li>
  <li><b>Standard Template Library (STL)</b></li>
  <li><b>SQLite3</b> (with C++ API)</li>
  <li><b>OpenSSL</b> for hashing passwords</li>
  <li><b>Makefile/CMake</b> for build automation</li>
  <li>Optional: Python for data visualization</li>
</ul>

<hr>

<h2>📊 Database Schema Overview</h2>

<pre>
Users(user_id, name, email, password_hash)
Accounts(account_id, user_id, account_type, balance)
Transactions(txn_id, user_id, amount, category, type, date)
Goals(goal_id, user_id, title, target_amount, deadline)
Investments(id, user_id, type, amount, start_date, rate)
AuditLogs(log_id, user_id, action, timestamp)
</pre>

<p>
Use <code>database/schema.sql</code> to initialize your database.
</p>

<hr>

<h2>🚀 How to Build and Run</h2>

<pre>
# Clone the repository
git clone https://github.com/yourusername/FinTrackPlusPlus.git
cd FinTrackPlusPlus

# Build the project
make   # or use g++ manually

# Run the executable
./fintrack
</pre>

<hr>

<h2>🛠️ To-Do Features</h2>
<ul>
  <li>GUI interface using Qt</li>
  <li>Firebase-based cloud sync</li>
  <li>REST API for mobile support</li>
  <li>UML & demo diagrams in /assets</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>
<p>
<b>Aditya Shankar Khorne</b><br>
Third-year Computer Science Engineering<br>
Savitribai Phule Pune University
</p>

<hr>

<h2>📄 License</h2>
<p>
This project is licensed under the <b>MIT License</b> – see the LICENSE file for details.
</p>

<hr>

<h2>⭐️ Support</h2>
<p>
If you find this project useful, consider giving it a ⭐️ and sharing it with friends, peers, or on LinkedIn!
</p>

