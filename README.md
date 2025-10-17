# ATM System

Proud to share my latest project: **ATM System**

I have developed a secure, interactive, and fully functional banking system using **React.js, Axios, JWT authentication, DOCX & PDF generation, and multilingual support**. This project allowed me to strengthen my skills in frontend development, backend integration, secure authentication, and user-centric design.

---

## Key Features of the Project

### User & Customer Features
- **English and Sinhala language support**
- **Card Transactions**: Users can log in securely using their card number and PIN, view balance, and perform withdrawals. After a successful transaction, they receive a confirmation notification.
- **Cardless Transactions**: Users can access their accounts using OTP verification and perform transactions without a physical card. After a successful transaction, they receive a confirmation notification.
- **Real-Time Transaction History**: Users can view all transactions and filter by the last 15 days, 1 month, 3 months, or all transactions — with details like type, amount, status, and balance after each transaction, along with notifications.
- **Cash Withdrawal with Denominations**: Users can select specific denominations for withdrawals.
- **Automatic Balance Updates**: Account balance updates in real time after each transaction.
- **Receipt Generation**: Users can download transaction receipts as PDF or DOCX files with details such as transaction ID, date, account number, amount, and new balance.
- **Change Password in ATM Card**: Users can change their card PIN using the old PIN, and upon success, receive a notification confirming the change.
- **Internationalization (i18n)**: Multilingual support for user-friendly interaction.
- **Session Timeout Management**: Automatically logs out inactive users to enhance security.
- **Home-Screen Ads**: Option to display promotional content — including video ads — on the ATM home screen to simulate real-world ATM advertising.

### Admin Features
- **Admin Dashboard**: Admins can log in and manage the system.
- **Denomination Monitoring**: If ATM denominations are insufficient, admins receive notifications and can check the available denominations.
- **Audit Access**: Admins and auditors can review transaction logs for transparency and security.

---

## Technical Highlights & Technologies Used
- **Frontend**: React.js, React Hooks, JSX, CSS, Responsive Design
- **State Management**: useState, useEffect, useRef
- **Routing**: React Router v6 (dynamic routes for user/account dashboards)
- **Backend**: Node.js (Express, LowDB for simple JSON persistence) powering RESTful endpoints
- **API Integration**: Axios for REST API calls with JWT token authentication
- **Security**: JWT token-based authentication for secure login

**File Generation**:
- **PDF Generation**: jspdf & jspdf-autotable for detailed transaction receipts
- **DOCX Generation**: docx & file-saver for downloadable Word documents

- **Date & Time Handling**: Filter transactions by date (last 15 days, 1 month, 3 months)
- **User Notifications & Alerts**: Display error messages, success messages, and notifications dynamically
- **Reusable Components**: Side navbars, session timeout, ad banners, transaction tables
- **UI/UX Enhancements**: Smooth scrolling, responsive buttons, dropdown menus, and interactive forms
- **Testing & Quality Focus**: The main focus was on implementing robust functionality and secure flows — I’m actively working on automated testing and improving UI/UX polish.

---

## What I Learned & Skills Strengthened
- Full-stack web development and secure client-server communication
- Handling asynchronous requests and managing state in React
- Generating dynamic reports in PDF & DOCX format
- Implementing user-centric design with attention to security
- Working with real-world banking scenarios like withdrawal breakdowns, denomination management, and admin notifications
- Building simulated hardware interactions (card insert simulation) and integrating ad/video playback in the UI

---

> 🧠 **Note**: This is a simulated ATM system — no physical hardware was used. To simulate card insertion, I used an input for card number + PIN. To simulate receipts, users can download them instead of printing in real time. The project mainly focuses on core functionality and secure server-client communication. I’m currently improving UI/UX design and working on testing modules.

---



