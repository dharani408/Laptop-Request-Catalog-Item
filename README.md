# 💻 Laptop Request Catalog Item (ServiceNow Project)

## 📌 Overview
This project automates laptop requests in **ServiceNow** using a Catalog Item with dynamic fields, UI Policies, and a Reset button.  
It replaces manual request methods (emails, spreadsheets) with a digital workflow that improves speed, reduces errors, and enhances user experience.

## ⚙ Features
- Laptop Request Catalog Item under **Hardware category**.
- Dynamic fields (e.g., Accessories Details visible only when needed).
- Reset button to clear form instantly.
- Update Set support for easy migration across instances.

## 🛠 Implementation Steps
1. Create Update Set  
2. Build Catalog Item  
3. Add Variables (Model, Justification, Accessories, Accessories Details)  
4. Configure UI Policies  
5. Create Reset Button (UI Action with JavaScript)  
6. Export & Import Update Set  
7. Test dynamic behavior and reset functionality  

## 📂 Project Files
- `Laptop_Request_Catalog_Simplified.pdf` → Simplified Project Report  
- `SI-32225-1757510409.docx` → Full Documentation  
- `resetForm.js` → UI Action Script  
- `update_set.xml` → Update Set Export (for import into target instance)  

## ✅ Benefits
- Faster laptop request processing  
- Reduced IT workload & errors  
- Portable across ServiceNow instances  
- Easy to extend with workflows & notifications  

## 🚀 Future Scope
- Approval workflows  
- Automated notifications  
- Dashboard integration  
- Mobile compatibility  

---

👨‍💻 *Developed as part of a ServiceNow learning project.*  
