# Emotion-Aware AI Chatbot

An AI-driven chatbot that understands the user's **emotional tone from speech** and responds with more empathetic, context-aware answers. The system combines a Flask backend with a Streamlit UI, and uses a speech emotion recognition pipeline powered by **Wav2Vec2** along with LLM responses via the **Cohere API**.

---

## 🚀 Key Features
- **Speech-based emotion recognition** using Wav2Vec2 (audio → emotion label)
- **Emotion-aware responses**: chatbot adapts tone based on detected emotion
- **Web UI built with Streamlit** for a simple, interactive user experience
- **Flask backend API** to handle inference + response orchestration
- Modular design to swap emotion model / LLM provider easily

---

## 🧠 How It Works
1. User provides voice input (audio)
2. Audio is processed and passed to **Wav2Vec2** to detect emotion
3. Detected emotion + user message is sent to the chatbot pipeline
4. **Cohere API** generates a response with the appropriate tone
5. Response is displayed in the Streamlit UI

---

## 🛠️ Tech Stack
- **Backend:** Python, Flask
- **Frontend/UI:** Streamlit
- **Speech Emotion Model:** Wav2Vec2
- **LLM / Text Generation:** Cohere API

---

## 📌 Skills / Concepts Demonstrated
- Speech processing & ML inference
- API design with Flask
- Rapid UI prototyping with Streamlit
- Prompting / response conditioning using emotion signals
- End-to-end integration of ML + web app

---

## 🌱 Future Enhancements
- Multi-language speech emotion detection
- Session memory + conversation history
- Better calibration of emotion confidence scores
- Deploy to cloud (Render/AWS) with a persistent backend

---

## 👩‍💻 Author
**Kashish Oswal**  
GitHub: https://github.com/Kashishoswal
