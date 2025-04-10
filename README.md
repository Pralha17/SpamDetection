# 📧 Spam Email Detection & Visualization using UiPath

This project automates the **detection of spam or repetitive emails** and visualizes patterns in the inbox using **UiPath** for automation and **Excel** for graphical representation. It leverages **Google Cloud Platform (GCP)** to securely access Gmail via **OAuth 2.0**.

---

## 🔍 Project Overview

The project was developed to:
- Automatically **detect and extract spam/repetitive emails** from a Gmail inbox.
- Analyze emails based on sender, subject, and keywords.
- Provide **visual reports and insights** via Excel charts.
- Implement **secure Gmail authentication** using OAuth 2.0 through **Google Cloud Console**.

---

## 🛠️ Tech Stack

- **Automation Tool**: UiPath  
- **Email Provider**: Gmail (accessed via Gmail API)  
- **Visualization Tool**: Microsoft Excel  
- **Authentication**: OAuth 2.0 using **Google Cloud Platform (GCP)**  
- **Languages**: No-code (UiPath workflows)

---

## 🔐 Gmail OAuth Setup via Google Cloud Platform (GCP)

To ensure secure and authorized access to Gmail, **Google Cloud Platform (GCP)** was used to configure **OAuth 2.0** credentials.

### Steps Followed:
1. Created a new project in [Google Cloud Console](https://console.cloud.google.com/).
2. Enabled the **Gmail API** for the project.
3. Set up the **OAuth consent screen** and added necessary scopes.
4. Generated **Client ID** and **Client Secret** under **OAuth 2.0 credentials**.
5. Used the credentials in **UiPath Gmail Scope activity** to authenticate.
6. Granted UiPath access via OAuth pop-up during bot execution.


---

## 🎯 Key Features

- ✅ Spam detection based on **keyword frequency and repetition**.
- ✅ Automatic extraction of email metadata (sender, subject, date).
- ✅ Excel-based **chart generation**:
  - Most frequent senders
  - Number of emails per day
  - Spam keyword distribution
- ✅ Smooth integration with Gmail using **OAuth 2.0**.

---

## 📂 Output

- Emails are saved in a structured Excel sheet.
- Visual insights include:
  - Bar chart of frequent senders
  - Line graph of daily email volume
  - Pie chart showing spam-related patterns

---

## 👨‍💻 Author

**Pralhad Agnihotri**  
📧 [pralhadagnihotri@gmail.com](mailto:pralhadagnihotri@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/pralhad24) | [GitHub](https://github.com/Pralha17)

