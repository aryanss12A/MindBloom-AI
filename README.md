# MindBloom-AI

🧠 MindBloom AI - Create Your Calm
A prototype developed for the GenAI Exchange Hackathon, focused on leveraging generative AI for youth mental wellness. MindBloom AI is a serverless web application designed as a safe, anonymous, and creative space for youth to navigate their emotional landscape. It turns mental wellness into an empowering act of creation, helping users express and understand their feelings through AI-generated art, stories, and sound.

✨ The Challenge
In a world of constant pressure, today's youth face significant challenges to their mental well-being. Many hesitate to seek help due to stigma, lack of access, or discomfort with traditional talk therapy. There is a critical need for accessible, engaging, and non-judgmental first-step tools for mental wellness.

💡 Our Solution: Creative-First Wellness
MindBloom AI addresses this challenge by providing a unique, creation-based approach. Our core belief is that expressing complex emotions through art, collaborative storytelling, and sound can be profoundly therapeutic. Instead of just offering static content, MindBloom AI uses Google's powerful generative AI models to co-create personalized experiences in real-time, tailored to the user's emotional state.

🚀 Features
Our prototype includes four fully functional, AI-powered wellness tools:

Feature

Description

<img width="837" height="570" alt="Screenshot (331)" src="https://github.com/user-attachments/assets/69339d16-4a61-45e9-832f-4d2cfdcaee18" />

🎨 Creative Canvas
Turns feelings and moods into unique, AI-generated images. Users type a prompt like "a calm, rainy afternoon" and watch the AI bring it to life.


<img width="827" height="547" alt="Screenshot (332)" src="https://github.com/user-attachments/assets/41a8fa24-f0c7-4739-a4ce-898caa4b7041" />

💬 AI Companion
An empathetic chatbot for 24/7 support. It provides a safe space for daily check-ins, guided reflection, and supportive conversations.


<img width="832" height="555" alt="Screenshot (333)" src="https://github.com/user-attachments/assets/ebff132f-359c-405d-9769-223b01eb5deb" />

✍️ Story Weaver
A collaborative writing tool where the user and the AI build short, therapeutic stories together, one line at a time, to explore emotions and scenarios.


<img width="805" height="540" alt="Screenshot (334)" src="https://github.com/user-attachments/assets/eb0f5c34-7b06-4fee-ae53-995dc0d79a81" />

🎵 Generative Soundscapes
Creates personalized, calming audio affirmations. Users select a theme like "Calm" or "Focus" to generate a short, soothing audio experience.

🛠️ Technology Stack & Architecture

The entire application is a single index.html file, making it incredibly lightweight and portable. It operates on a serverless architecture, making direct, secure API calls from the browser to Google Cloud's AI platform.

Frontend:

1.HTML5: The core structure of the web application.
2.Tailwind CSS: For the modern, responsive, and polished user interface.
3.JavaScript (ES6+): For all application logic, state management, and API communication.
4.Backend & AI Services (Google Cloud Platform):
5.Vertex AI (Imagen 3.0): Powers the text-to-image generation for the Creative Canvas.
6.Vertex AI (Gemini 2.5 Flash): Powers all text generation for the AI Companion and Story Weaver.
7.Vertex AI (Gemini TTS): Powers the text-to-audio generation for the Generative Soundscapes.

<img width="3840" height="1068" alt="1000079996" src="https://github.com/user-attachments/assets/0caf531c-35f5-4ced-929c-459fe8f0eb05" />

⚙️ How to Run
This prototype is designed for simplicity.

Clone the repository:
git clone [https://github.com/your-username/MindBloom-AI.git](https://github.com/your-username/MindBloom-AI)


