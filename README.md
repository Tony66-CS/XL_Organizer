# Excel Price Correction Tool 📊

This project is a simple Python script that processes an Excel workbook, applies a **10% discount** to prices, writes the corrected prices into a new column, and generates a **bar chart** based on the corrected values.

---

## 🚀 Features

* Reads data from an Excel file using **openpyxl**
* Applies a **10% price reduction**
* Writes corrected prices to a new column
* Automatically creates a **bar chart** for visualization
* Saves changes directly to the same Excel file

---

## 🛠 Requirements

Make sure you have Python installed, then install the required library:

```bash
pip install openpyxl
```

---

## 📁 Excel File Structure

Your Excel file must contain:

* A sheet named **`Sheet1`**
* Original prices in **Column C**
* Data starting from **row 2** (row 1 used for headers)

| A | B | C (Price) | D (Corrected Price) |
| - | - | --------- | ------------------- |
|   |   |           |                     |
|   |   | 100       | 90                  |

---

## ▶️ How It Works

1. Loads the Excel file
2. Reads each price from column **C**
3. Applies a 10% discount
4. Writes the corrected price to column **D**
5. Generates a **Bar Chart**
6. Saves the updated workbook

---

## 🧠 Usage

```python
process_workbook("transactions.xlsx")
```

Replace `"transactions.xlsx"` with your Excel file name.

---

## 📈 Output

* Corrected prices added to **Column D**
* A bar chart automatically inserted at cell **E2**

---

## 📌 Notes

* The original prices remain unchanged
* Running the script again will overwrite column **D**
* Ensure the Excel file is **closed** before running the script

---

## 📄 License

This project is for educational and personal use.

---

✨ Happy Coding!
