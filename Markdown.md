## 🧱 Object-Oriented Programming (OOP) Version

The upgraded version of **Advanced Time Management and Hour Calculator** is implemented using Object-Oriented Programming (OOP) principles to improve code structure, scalability, and maintainability.

Instead of handling all logic inside the main function, the system is organized into well-defined classes that separate responsibilities and promote clean architecture.

---

### 🏗 OOP Design Structure

The system may include the following classes:

- 🕒 **Time**
  - Stores hour and minute values
  - Converts time into total minutes
  - Validates time input

- ⏳ **WorkSession**
  - Accepts start and end time objects
  - Calculates total working duration
  - Handles overnight shifts

- 📊 **OvertimeCalculator**
  - Checks if working hours exceed standard limit (8 hours)
  - Computes overtime hours

- 🖥 **TimeManagementSystem**
  - Controls program flow
  - Handles user interaction
  - Displays final results

---

### 🎯 OOP Principles Applied

- 🔐 **Encapsulation**  
  Data and methods are grouped inside classes for better security and structure.

- 🧩 **Abstraction**  
  Complex time calculations are hidden behind simple method calls.

- 🔄 **Modularity**  
  Each class has a single responsibility, making the system easier to expand.

- ♻️ **Reusability**  
  Classes like `Time` and `WorkSession` can be reused in larger systems such as employee management software.

---

### 🚀 Advantages of OOP Version

- Cleaner and more organized code  
- Easier debugging and maintenance  
- Scal
