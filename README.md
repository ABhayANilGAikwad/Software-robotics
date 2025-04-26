# 🚀 **Automated Messaging Bot**

## 📌 **Introduction**

Communication is crucial for organizations today. Sending bulk messages manually via email and WhatsApp is both **time-consuming** and **error-prone**.

Our project, the **Automated Messaging Bot**, leverages **Automation Anywhere Community Edition** to automate sending **customized messages** to multiple users based on data sourced from a Microsoft Excel file. This solution ensures fast, **reliable**, and **efficient communication**, minimizing human intervention and potential errors.

---

## 💡 **Motivation**

Educational institutions and businesses often face challenges when distributing **information** like event invites, reminders, or important updates to large audiences. Manually composing and sending individual messages becomes impractical, especially with hundreds or thousands of recipients.

By automating these tasks, we reduce human effort, ensure **timely and accurate** communication, and increase operational efficiency. This bot is designed to solve these challenges by streamlining the messaging process.

---

## 🚧 **Problem Statement**

Manual communication processes often lead to:

- **Time consumption:** Requires significant effort for large recipient lists.
- **Human error:** Incorrect email addresses, typos, or missed recipients.
- **Inefficiency:** Mass communication becomes slow and error-prone for large participant lists.

Therefore, the need for an automated messaging bot becomes clear:

- **Read** participant details from an Excel file.
- **Send** personalized messages via Email (using SMTP) and WhatsApp (via web automation).
- Operate with **minimal human intervention**, ensuring **scalable** and **reliable** communication.

---

## 📝 **Brief Description**

The **Automated Messaging Bot** operates through the following steps:

1. **Data Extraction**  
   - Reads participant details (Name, Mobile Number, Email) from an Excel file.
  
2. **Personalized Email Communication**  
   - Composes a customized email for each participant and sends it using SMTP (e.g., Gmail).
  
3. **Personalized WhatsApp Communication**  
   - Sends personalized WhatsApp messages using the WhatsApp Web or `wa.me` links.
  
4. **Logging**  
   - Tracks the success or failure of each message, providing insights on delivery status.
  
5. **Resource Management**  
   - Ensures proper cleanup of resources like browser sessions and Excel files after execution.
  
6. **Scalability and Reliability**  
   - Designed to handle large recipient lists and deliver messages efficiently.

---

## 🛠️ **Tools Used**

| Tool/API                         | Purpose                                                                 |
|:----------------------------------|:------------------------------------------------------------------------|
| **Automation Anywhere**           | Main platform for creating and executing automation bots.              |
| **Microsoft Excel**               | Input source containing participant details (Name, Mobile Number, Email). |
| **SMTP Server (e.g., Gmail)**     | Protocol for sending email communication.                              |
| **Web Browser (e.g., Chrome)**    | Used for interacting with WhatsApp Web for message automation.         |
| **WhatsApp API (wa.me links)**   | Optional API for direct messaging via web browser links.               |
| **Python (optional)**             | For additional scripting or complex logic.                             |
| **AA360 Bot Assistant Extension** | Facilitates bot content copying between Automation Anywhere environments. |

---

## 🎯 **Objectives**

- **Automate** bulk messaging for email and WhatsApp.
- **Ensure** timely and error-free message delivery.
- **Minimize** human workload associated with manual communication.
- **Create** a reusable and scalable communication framework.
- **Facilitate bot sharing** across Automation Anywhere Community Edition environments.

---

## 🚀 **Why Automation?**

**Speed**  
- Send hundreds of messages in minutes, far quicker than manual methods.

**Accuracy**  
- Eliminate errors from manual typing and ensure consistent delivery.

**Scalability**  
- Efficiently handle large datasets extracted from Excel.

**Consistency**  
- Maintain uniformity in messaging format and delivery process.

**Efficiency**  
- Reduce human resource workload, letting employees focus on strategic tasks.

**Shareability**  
- Easily share the bot logic with other users via the **AA360 Bot Assistant**.

---

## 🔄 **Accessing and Importing the Bot using Bot Assistant**

Since Automation Anywhere Community Edition doesn't allow direct export/import of bots, use the **AA360 Bot Assistant Chrome Extension** to share and access bots.

### 🏷️ **Exporting the Bot (Source Environment)**

1. **Install the AA360 Bot Assistant Chrome Extension.**
2. **Open the Automated Messaging Bot** in your Automation Anywhere Control Room (either "View" or "Edit" mode).
3. **Launch the Bot Assistant Extension.**
4. Click the **"Copy to clipboard"** button to copy the bot’s JSON content.
5. **Share the copied JSON** with the user you want to access the bot.

---

### 📥 **Importing the Bot (Target Environment)**

1. **Install the AA360 Bot Assistant Chrome Extension.**
2. **Log in** to the Control Room of the target Automation Anywhere environment.
3. **Create a new Task Bot** (e.g., "Automated Messaging Bot - Imported").
4. **Open the bot in "Edit" mode.**
5. **Launch the Bot Assistant Extension.**
6. **Paste the JSON content** you received into the text area and click **"Patch Content."**
7. **Refresh** the Control Room page to see the bot's logic populate.

---

### ▶️ **Running the Bot (Target Environment)**

1. **Check Prerequisites:**
   - Ensure access to the correct Excel file and SMTP configuration.
   - Make sure WhatsApp Web is logged in on the browser.
   - Configure Python (if needed) for additional scripting.

2. **Navigate to the Bot** in the Control Room and click "Run."
3. Follow any prompts (e.g., specifying the Excel file path).
4. **Monitor execution** and check the logs for success/failure.

---

## 🔑 **Key Benefits of the Automated Messaging Bot**

- **Faster Communication**: Send multiple messages in a fraction of the time.
- **Error-Free**: Reduces the chances of mistakes that occur with manual messaging.
- **Scalability**: Handle hundreds or thousands of recipients with ease.
- **Time-Saving**: Eliminate the need for repetitive, manual tasks.
- **Reliability**: Ensure that messages are sent consistently without failure.

---

## 📚 **Conclusion**

The **Automated Messaging Bot** offers a solution to the inefficiencies of manual communication processes. By utilizing Automation Anywhere’s robust automation capabilities, this bot streamlines the entire process of sending bulk, personalized messages through both **email** and **WhatsApp**.

With an easy-to-follow setup, scalability, and the potential for future enhancements, the bot will significantly increase efficiency, ensuring seamless communication across various platforms.

---

## 📢 **Want to Try It?**

1. Install the **AA360 Bot Assistant Extension**.
2. **Export or Import** the bot as needed.
3. Run the bot and **start automating your communications**!

For any questions or support, feel free to reach out. Enjoy automating! 🌟
