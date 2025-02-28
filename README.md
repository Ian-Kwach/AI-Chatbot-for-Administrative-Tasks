🤖 AI Chatbot for Administrative Tasks
🚀 Automate your workflow with a powerful AI-driven chatbot!
This Python-based chatbot uses Natural Language Processing (NLP) and Deep Learning to understand and execute various administrative tasks, improving efficiency and reducing manual work.

📌 Features
✅ Writes and sends emails 📧
✅ Edits PowerPoint presentations 📊
✅ Signs PDFs electronically ✍️
✅ Downloads files from URLs 📂
✅ Sends Telegram messages 💬
✅ Schedules meetings in Google Calendar 📅
✅ Generates reports (PDF/Excel) 📑
✅ Uses a trained RNN model for conversation handling 🧠

🛠️ Tech Stack
Programming Language & Frameworks
🐍 Python 3 – Core language for AI chatbot development
🤖 TensorFlow/Keras – Deep Learning (RNN model)
🗣️ NLTK (Natural Language Toolkit) – Text processing
🔧 Flask – Web API deployment (optional)
Libraries Used
Library	Purpose
nltk	Text tokenization & NLP
tensorflow, keras	Neural network training
numpy, pandas	Data processing
Flask	Web API for chatbot
requests	File download automation
python-telegram-bot	Telegram messaging
python-pptx	PowerPoint editing
reportlab, PyMuPDF	PDF signing & generation
oauth2client, google-api-python-client	Google Calendar API
📂 Project Structure
bash
Copy
Edit
chatbot-admin-assistant/
│── chatbot.py                 # Main chatbot script
│── model_training.py           # Neural network training script
│── intents.json                # Training data for chatbot
│── requirements.txt            # Python dependencies
│── email_utils.py              # Email automation functions
│── ppt_utils.py                # PowerPoint editing functions
│── pdf_utils.py                # PDF signing functions
│── telegram_utils.py           # Telegram messaging functions
│── calendar_utils.py           # Google Calendar scheduling functions
│── reports.py                  # PDF/Excel report generation
│── README.md                   # Project documentation
🚀 Installation & Setup
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/chatbot-admin-assistant.git
cd chatbot-admin-assistant
2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Prepare Training Data
Ensure the intents.json file is correctly structured before running the chatbot.

4️⃣ Train the Chatbot Model
bash
Copy
Edit
python model_training.py
This step trains the RNN model for text classification.

5️⃣ Run the Chatbot
bash
Copy
Edit
python chatbot.py
📝 Usage Guide
💌 Send an Email
plaintext
Copy
Edit
You: Send an email
Chatbot: Sure! Enter the recipient's email, subject, and body.
➡️ Automates email sending using SMTP.

📊 Edit PowerPoint
plaintext
Copy
Edit
You: Edit PowerPoint
Chatbot: Which PowerPoint file should I edit?
➡️ Updates slides, adds text/images dynamically.

✍️ Sign PDFs
plaintext
Copy
Edit
You: Sign PDF
Chatbot: Upload the PDF file and the signature image.
➡️ Adds a digital signature to PDFs automatically.

📂 Download a File
plaintext
Copy
Edit
You: Download file
Chatbot: Enter the file URL and save location.
➡️ Fetches files from the web and saves them locally.

💬 Send Telegram Messages
plaintext
Copy
Edit
You: Send Telegram message
Chatbot: Provide the Telegram Bot Token, Chat ID, and message.
➡️ Sends messages to Telegram using Bot API.

📅 Schedule a Meeting
plaintext
Copy
Edit
You: Schedule meeting
Chatbot: Enter the meeting title, date, and time.
➡️ Creates a Google Calendar event via API.

📑 Generate Reports
plaintext
Copy
Edit
You: Generate report
Chatbot: What type of report do you need? I can create an Excel or PDF report.
➡️ Automatically generates structured reports.



💡 Future Improvements
🔍 Add GPT-4 Integration for better responses.
🖼️ Image Processing in reports and PDFs.
🌍 Multilingual Support for global users.

👨‍💻 Author
Kwach
📧 Email: iankwach00@gmail.com
🌍 GitHub: Ian-Kwach
