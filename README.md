# attendance-to-dtr
Converts raw attendance data into a formatted Daily Time Record (DTR) sheet ready for printing.

# 🕒 Attendance to DTR Converter (ExcelJS)

A lightweight web-based tool that converts attendance Excel files into **printable Daily Time Record (DTR)** sheets.  
Built with **HTML**, **JavaScript**, and **ExcelJS**, this system helps HR and payroll teams format attendance reports automatically — no manual Excel work needed.

---

## 🚀 Features
- 📂 Upload attendance Excel files (`.xlsx` or `.xls`)
- 🧾 Automatically extracts cut-off dates from the filename  
  _(e.g., `09-01-2025_TO_09-15-2025.xlsx` → displays “September 1, 2025 to September 15, 2025”)_
- 👨‍💼 Displays employee list with checkboxes to include/exclude names
- 🔤 Sort employee names A–Z or select/deselect all
- 🖨️ Generates formatted DTR Excel file (landscape orientation, borders, and proper layout)
- 📄 Page breaks automatically added per employee for clean printing
- ✍️ Includes signature section and cut-off period in the generated report

---

## 🧩 Built With
- **HTML5**
- **JavaScript (ES6)**
- **ExcelJS 4.3.0**

---

## ⚙️ How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/attendance-dtr-converter.git
