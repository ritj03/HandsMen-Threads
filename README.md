# 👔 HandsMen Threads – Salesforce CRM Project

**HandsMen Threads** is a real-world Salesforce CRM solution tailored for inventory tracking, order management, and marketing automation. Built using Apex, triggers, custom objects, and flexipages, this project showcases modular and scalable metadata architecture for a retail-oriented application.

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
