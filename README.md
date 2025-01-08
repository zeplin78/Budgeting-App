# Budgeting App
### welcome page
![Screenshot (134)](https://github.com/user-attachments/assets/b0f91555-1ee9-46dc-b62e-3f0d3f817dee)

### Budgets page
![Screenshot (135)](https://github.com/user-attachments/assets/7a1e4cc6-ca8d-4159-a959-e8dc6c3cd637)

## 📌 Overview
The **Budgeting App** is a web application designed to help users track their income and expenses efficiently. Built using **React**, it leverages modern React features like Hooks and Context API to manage state and ensures data persistence through local storage. The app is lightweight, responsive, and user-friendly, providing a clean interface for financial tracking.

---

## 🛠 Features
- **Add Transactions**: Record income or expense entries with a description and amount.
- **Delete Transactions**: Easily remove transactions from the list.
- **Real-Time Balance Updates**: Automatically update the balance as transactions are added or removed.
- **Transaction History**: View a comprehensive list of all past transactions.
- **Persistent Storage**: Saves data to the browser's local storage for continued access across sessions.
- **Responsive Design**: Optimized for mobile and desktop devices.

---

## 💻 Technologies Used

### **Frontend**
#### **React**
- **Components**: Reusable and modular components like `TransactionList`, `AddTransaction`, and `Header` simplify the app structure and improve maintainability.
- **React Hooks**:
  - `useState` for managing component-level state.
  - `useEffect` for lifecycle management, such as syncing data to local storage.
- **React Context API**:
  - Used to create a global state for managing transactions and balance efficiently without prop drilling.

#### **CSS**
- **Styled Components**: Implements modern and maintainable styling.
- **Flexbox & Grid**: Used for responsive layouts.
- **Media Queries**: Ensures the app adapts seamlessly to various screen sizes.

### **Storage**
#### **Local Storage**
- Saves user data in the browser, ensuring the app is lightweight and does not require a backend for data storage.

### **Tooling**
- **Node.js & npm**:
  - For dependency management and running the React development server.
- **ESLint & Prettier**:
  - Maintains code quality and formatting consistency.

---

## 🚀 Getting Started

### Prerequisites
- Node.js and npm installed on your local machine.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/zeplin78/Budgeting-App.git
   cd Budgeting-App
2. Install dependencies:
   ```bash
   npm install
3. start the development server: 
   ```bash
   npm start
4. Open the app in your browser: http://localhost:3000

  
### 🌟 Key Concepts
- React component-based architecture for scalable UI development.
- State management with Hooks and Context API.
- Local storage for persistent client-side data handling.
- Responsive web design with modern CSS techniques.

### 🌟 Future Enhancements
- User Authentication: Allow users to create accounts and save transactions to their profiles.
- Database Integration: Replace local storage with a backend solution like MongoDB or Firebase for improved scalability.
- Data Visualization: Include graphs and charts for better insights into spending habits.


