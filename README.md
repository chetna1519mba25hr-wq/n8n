 Overview

This project demonstrates an automated workflow that processes data from Google Sheets and classifies entries into different performance categories (High, Average, Low). The system uses conditional logic to evaluate data and automatically store results back into a Google Sheet.

It is designed to reduce manual effort and improve efficiency in data handling and decision-making.

---

## Workflow Screenshot

![Workflow](./Screenshot.png)
<img width="1266" height="607" alt="image" src="https://github.com/user-attachments/assets/cc91dd5e-a69e-4a10-ab58-74cd256d7923" />


---

##  Features

*  Automated data trigger from Google Sheets
*  Data preprocessing using Edit Fields
* Conditional logic using Switch nodes
* Performance classification (High, Medium, Low)
*  Automatic data storage in Google Sheets
* ⚡ Real-time workflow execution

---

##  Workflow Architecture

### 1. Google Sheets Trigger

* Detects updates or new entries in the sheet
* Starts the workflow automatically

### 2. Data Processing (Edit Fields)

* Cleans and formats incoming data
* Prepares fields for classification

### 3. Conditional Logic (Switch Nodes)

* Data is categorized into:

  * High Performance
  * Medium Performance
  * Low Performance

### 4. Branch Processing

* Each category is processed separately
* Custom logic can be applied per category

### 5. Final Output

* Processed data is appended back to Google Sheets

---

##  How It Works

1. A new or updated entry is detected in Google Sheets
2. Data is cleaned and structured
3. Conditions are applied using Switch nodes
4. Based on values, data is classified into categories
5. Final results are stored back into the sheet

---

## Components Used

* Google Sheets Trigger
* Edit Fields Nodes
* Switch Nodes (Rule-based logic)
* Google Sheets (Append Row)

---

## Use Cases

* Employee performance tracking
* Student result classification
* Sales performance analysis
* Data automation workflows

---

##  Limitations

* Depends on correct input data
* Rule-based (not AI-driven)
* Requires manual configuration of conditions

---

##  Future Improvements

* Add AI-based prediction
* Integrate dashboards (Power BI / Tableau)
* Real-time notifications (Email/Slack)
* Advanced analytics

---

##  Author

Developed as part of an automation and data processing project.

---

## 📄 License

This project is for educational purposes.
