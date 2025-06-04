🧠 Smart Image Chatbot with Speech Synthesis
Smart Image Chatbot is an AI-powered web application that allows users to upload an image, receive a descriptive caption, extract any text within the image, ask questions about it, and hear the answer read aloud. This chatbot enhances accessibility and interaction with visual content — especially helpful for visually impaired users.

✨ Features
🖼️ Image Upload – Users can upload any image

✍️ Image Captioning & OCR – Captions the image and extracts text using Optical Character Recognition

❓ Visual Question Answering – Users can ask questions about the image

🔊 Speech Synthesis – Answers are spoken aloud using gTTS (Google Text-to-Speech)

🌐 Gradio Web Interface – User-friendly web app for interaction

🚀 How to Run
1️⃣ Install Dependencies
bash
pip install -r requirements.txt

2️⃣ Add API Key
Create a .env file based on .env.example
Add your Cohere API key:
ini
COHERE_API_KEY=your_key_here

3️⃣ Start the App
bash
python main.py
🔎 Sample Output
Input: Image of a laptop advertisement
Caption: "A laptop with text describing its features"
OCR: "Intel i5 8GB RAM SSD 512GB"
Q: "What are the laptop specs?"
Answer: "The laptop has an Intel i5 processor, 8GB RAM, and a 512GB SSD."
Audio: Answer is read aloud using TTS

🧩 File Structure
bash
Copy
Edit
├── main.py           # Gradio web app
├── utils.py          # Captioning, OCR, QA, TTS helpers
├── requirements.txt  # Project dependencies
├── .env.example      # Example environment file
├── README.md         # Project documentation
└── .gitignore        # Files to ignore in version control

📌 Requirements
Python 3.7+
Cohere API key
Internet connection (for API calls and TTS)

💡 Future Scope
Multi-language support
Real-time image capture via webcam
Better TTS options and natural-sounding voices
Deploy on Hugging Face Spaces or Streamlit Cloud

🤝 Contributions
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📜 License
This project is open-source and available under the MIT License.
