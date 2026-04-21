# 📦 Plan-to-Produce Process in SAP PP

### 🏭 Case Study: Tata Electronics

---

## 📌 Overview

This project demonstrates the **Plan-to-Produce (P2P)** process using the **SAP PP** module in an ERP system.

It provides a complete walkthrough of how a manufacturing company plans, executes, and tracks production — from demand forecasting to final product delivery.

The case study simulates a real-world manufacturing scenario of smartphone production at Tata Electronics.

---

## 🎯 Objectives

- Understand the **end-to-end P2P cycle**
- Learn key SAP PP **transaction codes (T-Codes)**
- Demonstrate **integration with SAP MM and FI modules**
- Analyze production efficiency and inventory management

---

## 🏭 Case Study Details

| Parameter | Details                      |
|----------|------------------------------|
| Company  | Tata Electronics             |
| Product  | Smartphone Model X           |
| Quantity | 100 Units                    |
| Location | Hosur Plant                  |
| Timeline | 5 Days                       |
| Customer | TechZone Retail, Bhubaneswar |

---

## 🔄 P2P Process Flow# sap_p2p
Demand Planning → MRP → Planned Order → Production Order →
Goods Issue → Confirmation → Goods Receipt
---

## ⚙️ SAP PP Process Steps

### 1. Demand Planning
**T-Code:** `MD61`

- Create Planned Independent Requirements (PIRs)
- Based on forecasts and customer demand

---

### 2. Material Requirement Planning (MRP)
**T-Code:** `MD01`

- Checks inventory levels
- Generates planned orders
- Triggers procurement if needed

---

### 3. Stock Overview
**T-Code:** `MD04`

- Displays real-time stock status
- Shows shortages and incoming materials

---

### 4. Production Order Creation
**T-Code:** `CO01`

- Converts planned orders into production orders
- Includes:
  - Bill of Materials (BOM)
  - Routing
  - Work centers

---

### 5. Goods Issue
**T-Code:** `MB1A`

- Issues raw materials to production
- Updates inventory and cost

---

### 6. Production Confirmation
**T-Code:** `CO11N`

- Records actual production data
- Tracks labor, machine usage, and progress

---

### 7. Goods Receipt
**T-Code:** `MIGO`

- Adds finished goods to inventory
- Updates accounting records

---

## 🔗 Module Integration

| Module | Function              |
|--------|----------------------|
| SAP PP | Production Planning  |
| SAP MM | Inventory & Materials|
| SAP FI | Financial Accounting |

---

## ✅ Key Outcomes

- ✔ Efficient production of 100 units
- ✔ Accurate inventory tracking
- ✔ Reduced manual errors
- ✔ Real-time production monitoring

---

## 🚀 Key Benefits

- Automation of production workflows
- Real-time visibility of operations
- Improved inventory accuracy
- Better resource utilization
- Reduced production delays
- Enhanced cost control

---

## 🖼️ Screenshots (To be Added)

- MD61 – Demand Planning  
- MD01 – MRP Run  
- CO01 – Production Order  
- MB1A – Goods Issue  
- CO11N – Confirmation  
- MIGO – Goods Receipt  

---

## 📊 Future Scope

- Migration to **SAP S/4HANA**
- Integration with **IoT-enabled smart factories**
- AI-based demand forecasting
- Predictive maintenance using machine learning
- Advanced analytics via SAP Analytics Cloud
- Automation using RPA (Robotic Process Automation)

---

## 📚 Learning Outcomes

- Practical understanding of SAP PP workflows
- Real-world manufacturing simulation
- ERP system integration concepts
- Production lifecycle management

---

## ⚠️ Disclaimer

This project is created for **academic purposes only**.  
All company data and transactions are **simulated** and do not represent real operational data.

---

## 👩‍💻 Author

**Tanishq Sahoo**  
B.Tech (CSE) – 3rd Year  
KIIT University
