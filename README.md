🤖 AI-Enhanced Workflow Automation with n8n
Overview
This repository showcases two powerful automation workflows built during the NxtWave Workflow Automation Workshop using n8n:

1. AI-Powered Chat Email Sender

2. Google Forms Auto-Response System

Both workflows demonstrate how AI + automation can work together to handle real-world communication scenarios intelligently and efficiently.

🔧 Workflow 1: AI-Powered Email Sender
🛠️ Tools Used
n8n

LangChain Integration

Google Gemini 1.5 Flash (PaLM)

Google Sheets

Gmail

📋 Workflow Description
This workflow allows you to send an email based on a natural language chat input.

Flow:
Trigger: Chat message received

AI Agent: Extracts recipient name, email (if present), subject, and body

Google Sheets Tool: If email is missing, it looks it up by name

Gmail Tool: Sends a personalized email to the user

Example:
Input:

"Send an email to Anil Kumar saying 'You're shortlisted!'"

✅ Output:
An email is sent to anilkumartamada69@gmail.com with the message automatically!

🔧 Workflow 2: Google Forms Auto-Responder
📋 Workflow Description
Automatically responds to a form submission using data from Google Sheets.

Flow:
Trigger: Google Sheets detects a new row

Extract: Name and Email

Send: Acknowledgment email via Gmail

✅ Use Case
Job application response

Registration confirmation

Feedback collection


📚 Learn More
n8n Docs

LangChain

Google Gemini

💡 Conclusion
These workflows demonstrate how AI + automation can streamline everyday tasks like messaging and form handling. This is just the beginning — more ideas coming soon!


![Screenshot 2025-07-05 153946](https://github.com/user-attachments/assets/6c077589-bc08-47d6-9abc-6c4702402a43)

![Screenshot 2025-07-05 153939](https://github.com/user-attachments/assets/7390c0de-fe35-4439-a109-2bb8bf020fbd)

![Screenshot 2025-07-05 153928](https://github.com/user-attachments/assets/3fa65cdd-e1ef-4aa2-be1f-0bb88cbc649a)

![Screenshot 2025-07-06 121335](https://github.com/user-attachments/assets/5e58138b-b697-449a-a9fd-f7fca173152b)

![Screenshot 2025-07-06 121325](https://github.com/user-attachments/assets/76fe7a34-55d2-48ba-8e75-1dee3a115000)

![Screenshot 2025-07-06 121315](https://github.com/user-attachments/assets/01ecfe2e-be79-4ba7-a96f-eacd8c6122d3)


