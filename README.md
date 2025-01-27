# Order-Management-App
### **1. Project Title**
**Order Management App**  
*A simple app designed to connect with Dynamics 365 Orders, display order lists, and allow drill-down functionality for individual order details.*

---

### **2. Project Description**
The **Order Management App** is a model-driven app created using Microsoft PowerApps and Dynamics 365. It demonstrates the ability to integrate with Dynamics 365 data entities, specifically the Orders table, to provide a user-friendly interface for managing and viewing orders.

Key features include:  
- Displaying a list of orders from the Dynamics 365 Orders table.  
- Drill-down functionality to view detailed information about a specific order.  
- A simple, intuitive UI built for compatibility with AppSource.

---

### **3. Features**
- **Order List View**: Displays active orders, including fields such as Order ID, Customer Name, Status, and Total Amount.
- **Drill-Down Feature**: Allows users to click on an order to see its detailed information, including order items and shipping details.
- **PowerApps Integration**: Fully connected with Microsoft Dataverse for data retrieval and updates.
- **AppSource Compatibility**: Designed to meet AppSource requirements for publishing.

---

### **4. Setup Instructions**
#### **Prerequisites**
1. A Microsoft Dynamics 365 account (trial or existing).
2. Access to the PowerApps Maker portal ([https://make.powerapps.com/](https://make.powerapps.com/)).
3. Admin access to a Power Platform environment.

#### **Steps to Import the App**
1. Clone this repository to your local machine:  
   ```bash
   https://github.com/giftahmed/Order-Management-App.git
   ```
2. Log in to [PowerApps Maker Portal](https://make.powerapps.com/).
3. Navigate to **Solutions** > **Import Solution**.
4. Upload the `OrderManagementApp_1_0_0_1_managed.zip ` file from the repository.
5. Follow the prompts to import the solution into your environment.
6. Open the imported solution, and click **Publish All Customizations**.

---

### **5. Demo Video**
Watch a walkthrough of the app's features and codebase:  
**[Demo Video Link](https://youtu.be/6IWDDtsbj58)**

---

### **6. Code Overview**
#### **Folder Structure**
- **/Order Management App**: Contains exported PowerApps solution files.
- **README.md**: This documentation file.

#### **Technologies Used**
- **Microsoft PowerApps** for app design.
- **Microsoft Dataverse** for data storage and management.
- **Dynamics 365 Orders Entity** for data integration.

---

### **7. App Functionality**
- **Orders View**: Displays the list of orders retrieved from the Dataverse.
- **Drill-Down**: Provides detailed information about a single order.
- **Customization**: Designed for easy extensibility and integration with other entities or tables in Dynamics 365.
