# 👔 HandsMen Threads – Salesforce CRM Project

**HandsMen Threads**, a dynamic organization in the fashion industry, is embarking on a Salesforce project designed to revolutionize their data management and enhance customer relations. The project involves building a robust data model tailored to store all pertinent business data, ensuring a seamless flow of information across the organization.

A key aspect of this project is the maintenance of data integrity directly from the user interface (UI). This feature will safeguard the accuracy and consistency of the data, which is crucial for informed decision-making and reliable business operations.The project will integrate several new processes into the business workflow to improve customer service and operational efficiency:

**Automated Order Confirmations**: Post-order confirmation, customers will receive an email update, fostering engagement and strengthening customer relations.

**Dynamic Loyalty Program**: Customer loyalty statuses will be updated based on purchase history, enabling personalized rewards and promoting repeat business.

**Proactive Stock Alerts**: When stock levels drop below five units, automatic emails will notify the warehouse team, ensuring timely restocking and preventing stockouts.

**Scheduled Bulk Order Updates**: Daily midnight, the system will process bulk orders, updating financial records and adjusting inventory, ensuring accurate stock levels for daily operations.

---

## 📦 Modules & Metadata

### 🔧 Apex Classes
- `InventoryBatchJob.cls`: Manages scheduled inventory updates
- `OrderTriggerHandler.cls`: Encapsulates logic for order-based triggers

### 🔄 Apex Triggers
- `OrderTrigger.trigger`: Handles order creation logic
- `OrderTotalTrigger.trigger`: Calculates and updates order totals
- `StockDeductionTrigger.trigger`: Deducts stock based on fulfilled orders

### 🧩 Custom Objects
- `HandsMen_Product__c`: Defines product catalog
- `HandsMen_Order__c`: Captures customer purchase details
- `HandsMen_Customer__c`: Stores customer profiles
- `Inventory__c`: Tracks available stock
- `Marketing_Campaign__c`: Manages campaign activity

### 🎛️ UI & Layouts
- `HandsMen_Threads_UtilityBar.flexipage`: Adds quick-access tools to the utility bar

---

## 🛠️ Features Implemented

- ✅ Order-to-stock deduction with business logic
- ✅ Real-time order total updates via triggers
- ✅ Custom metadata architecture with clear naming conventions
- ✅ Modular Apex handler classes for cleaner code reuse
- ✅ Declarative UI enhancements using Flexipage

---

## 🧠 Project Inspiration
This project was designed for hands-on learning and demonstration of:
- Real-world Apex logic
- Trigger optimization techniques
- Custom object modeling
- Declarative and programmatic UI integration
