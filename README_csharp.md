# PMD2 Data Monitoring Project (C# Version)


## 🔧 Key Features

### ✅ Real-time Data Monitoring
- Displays sensor data from three regions: **ATX24, EPS, and PCIE & HPWR**
  - Voltage
  - Current
  - Power

### ✅ Device Connection
- Click `Connect Device` to establish the connection  
- Then click `Start Read` to begin data acquisition

### ✅ CSV Export
- Export current sensor data to a **horizontally formatted CSV file** based on user-selected fields  
- The filename includes a **timestamp**

### ✅ CSV Settings
- A dialog allows users to select which fields to export  
- The settings are saved to a **JSON file**, which is automatically loaded the next time the app starts

### ✅ Graphing Function
- Click `Open Graph Window` to open a real-time chart display for all channels

### ✅ Calibration Features
- `Reset`: Resets all calibration parameters to default values (gain = 1.0, offset = 0.0)  
- `Write`: Updates the global calibration parameters and applies them to real-time display and max/min logging  
- `Load`: Loads saved calibration parameters from a JSON file and updates the UI  
- `Store`: Saves the current parameters from the UI to a JSON file for automatic loading next time

### ✅ Fixed Window Size
- The main window and all dialogs have **fixed dimensions** and cannot be resized

---

[🔁 Switch to Traditional Chinese](README_csharp_zh.md)
