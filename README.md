# Inventory Management Dashboard

A full-stack inventory management dashboard designed to streamline and optimize inventory tracking and management processes.

---

## 🛠️ Tech Stack

### Frontend

- Next.js
- Tailwind CSS
- Redux Toolkit
- Redux Toolkit Query
- Material UI Data Grid

### Backend

- Node.js
- Prisma

### Deployment & Cloud Services

- AWS EC2
- AWS RDS
- AWS API Gateway
- AWS Amplify
- AWS S3

---

## 📁 Project Structure

- `client/` - Contains the frontend application built with Next.js.
- `server/` - Houses the backend API developed using Node.js and Prisma.

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn
- AWS account with necessary permissions

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/sathvik-23/inventory-management.git
   cd inventory-management
   ```

2. **Install dependencies for both frontend and backend:**

   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. **Configure environment variables:**

   Create a `.env` file in both `client/` and `server/` directories and add the necessary environment variables as per your setup.

4. **Run the development servers:**

   - **Frontend:**

     ```bash
     cd client
     npm run dev
     ```

   - **Backend:**

     ```bash
     cd server
     npm run dev
     ```

---

## 🧪 Features

- Real-time inventory tracking
- CRUD operations for products
- Responsive and intuitive UI with Material UI Data Grid
- State management using Redux Toolkit
- API integration with Redux Toolkit Query
- Secure and scalable backend with Node.js and Prisma
- Deployment-ready with AWS services

---

## 📦 Deployment

The application is configured for deployment using AWS services:

- **Frontend** deployed via AWS Amplify
- **Backend API** managed through AWS API Gateway and hosted on AWS EC2
- **Database** hosted on AWS RDS
- **Static assets** stored in AWS S3

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
