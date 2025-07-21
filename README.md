# ♻️ RePlastix Innovations: Transforming Plastic Waste into Sustainable Solutions

## 📘 Salesforce CRM Documentation

### 1. 📌 Project Overview
RePlastix Innovations is a Salesforce CRM solution tailored to support a circular economy. It manages plastic waste collection, recycling, product distribution, and restock logistics. The system uses custom objects, flows, Apex classes, triggers, and scheduled logic to automate end-to-end operations.

---

### 2. 🎯 Objectives
- Automate key processes such as restock generation and inventory tracking.  
- Improve coordination across recycling centers, production teams, and order management.  
- Enforce role-based access and validation to reduce human error.  
- Provide real-time environmental and operational insights via reports and dashboards.

---

### 3. 📝 Phase 1: Requirement Analysis & Planning
- Identified core entities: Plastic Waste, Recycled Products, Orders, Restock Requests, and Recycling Centers.  
- Created custom objects:
  - `Re_Plastic_Innovations_Plastic_Waste__c`  
  - `Re_Plastic_Innovations_Recycled_Product__c`  
  - `Re_Plastic_Innovations_Order__c`  
  - `Re_Plastic_Innovations_Restock_Request__c`  
  - `Re_Plastic_Innovations_Recycling_Center__c`  
- Defined object relationships, business rules, field types, and automation needs.

---

### 4. 🔧 Phase 2: Salesforce Development – Backend & Configurations
- Built custom fields, validation rules, and relationships via Object Manager.  
- Developed **Flows**:
  - Auto Restock Trigger Flow  
  - Inventory Stock Alert Flow  
- Developed **Apex Classes**:
  - `InventoryManager.cls`  
  - `InventoryManagerTest.cls`  
- Designed custom email alerts for inventory and order notifications.

---

### 5. 🖥️ Phase 3: UI/UX Development & Customization
- Created a Lightning App: **Re Plastic Innovations**  
- Added navigation tabs for all key custom objects.  
- Designed Lightning Pages with dynamic forms and field visibility rules.  
- Ensured intuitive layouts for each user role.

---

### 6. 🔐 Phase 4: Data Migration, Testing & Security
- Imported sample data using **Data Loader** and **Data Import Wizard**.  
- Created user roles:
  - `Plant Manager`  
  - `Production Manager`  
  - `Warehouse Supervisor`  
- Applied permission sets, field-level security, and ACLs.

---

### 7. ✅ Testing and Quality Assurance
- Achieved over **85% test coverage** for Apex logic.  
- Used **Flow Debug Logs** to validate automation.  
- Manually tested Lightning UI across profiles.  
- Verified stock levels and workflow executions post-trigger events.

---

### 8. 🚀 Phase 5: Deployment, Documentation & Maintenance
- Deployed using **Change Sets** and **Salesforce CLI (SFDX)**.  
- Maintained source control via Git and pushed metadata to GitHub.  
- Included comprehensive documentation and test screenshots.

📂 **Documentation File:** `RePlastix_Innovations_Salesforce_Project.pdf`

---

### 9. 🌟 Future Enhancements
- 🔗 **IoT Integration** for smart bin-to-inventory tracking  
- 📈 **Sustainability Dashboards** to report CO₂ offset and waste recycled  
- 🧠 **AI Forecasting** for predicting restock needs  
- 🌐 **Partner Portal** for recycling agencies and municipalities  
- 📊 **Einstein Analytics** for ESG reporting and advanced metrics

---

### 10. 🧾 Conclusion
This Salesforce CRM solution for RePlastix Innovations demonstrates a scalable, automation-first approach to managing plastic recycling workflows. It enhances visibility, improves data integrity, and drives sustainability outcomes—laying the foundation for a smart, eco-friendly future.

---

### 👨‍💻 Developer & Contact

- **Name:** Sharanya Lakshmi S N
- **Email:** 224g1a3288@srit.ac.in  
- **Role:** Salesforce Developer  
- **Project Status:** ✅ Completed

---

