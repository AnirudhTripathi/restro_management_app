
# Restaurant Control and Management System

Welcome to this repository, a comprehensive management solution for restaurants that includes inventory control, supplier management, order tracking, and an interactive dashboard for an overview of the system. Developed by the startup, our platform provides an intuitive, scalable system to meet restaurants’ operational needs efficiently.

## 📖 About the Product
 It's a tech company focused on developing management systems for the food sector. Our main product is an app for restaurants, offering three customizable plans to suit each establishment's needs. Key features include:

- **Virtual Inventory Control**
- **Supplier Management**
- **Order Monitoring**
- **Dashboard for System Overview**

## ✨ Features

### 1. Virtual Inventory Control 📦
Manage stock products efficiently:
- Product data management with:
  - **Product Name and Description**
  - **Supplier** and **Identification Code**
  - **Unit Price**, **Unit of Measure**, and **Current Quantity**
  - **Expiration Date** and **Product Image**
  - **Maximum and Minimum Stock Quantities**

- **Stock Management**:
  - Update quantities manually with each movement.
  - Automatic alerts for minimum stock or nearing expiration dates.

### 2. Supplier Management 🤝
Add and manage suppliers for efficient restocking:
- Detailed supplier information:
  - **Supplier Name**
  - **Supplied Products**
  - **Address and Postal Code**
  - **Phone, Email, and Tax ID**
  - **Delivery Time**

### 3. Order Monitoring 📋
Real-time order tracking, from preparation to delivery, with potential mobile integration:
- Add and edit new dishes.
- **Order Management**:
  - Create, edit, delete, and finalize orders.
  - Filter by status: **New**, **In Preparation**, and **Completed**.
  - View preparation time, price, and attendant name.
  - Automatically updates stock after completion, deducting used ingredients.

### 4. Dashboard 📊
Monitor essential metrics visually:
- Metrics on:
  - **Stock Capacity**
  - **Top Products in Demand**
  - **Peak Order Days**
  - **Average Sales**
  - **Supplier Delivery Time**

## 🛠️ Technologies Used

- **Backend**: [C#.NET](https://learn.microsoft.com/pt-br/dotnet/csharp/tour-of-csharp/) and [ASP.NET](https://dotnet.microsoft.com/pt-br/apps/aspnet)
- **Frontend**: [Avalonia UI Framework](https://avaloniaui.net/)
- **Database**: [MongoDB](https://www.mongodb.com/pt-br/docs/drivers/csharp/current/)
- **UI Design**: [XAML](https://docs.avaloniaui.net/docs/basics/user-interface/introduction-to-xaml)

## 🚀 How to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/AnirudhTripathi/restro_management_app.git
   ```
2. Install dependencies:
   ```bash
   cd rango
   npm install
   ```
3. Start the system:
   ```bash
   npm start
   ```
