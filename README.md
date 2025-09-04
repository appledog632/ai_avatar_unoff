# Millie-AI 🤖


Millie is an AI-powered chatbot designed specifically for university environments, with a focus on providing information related to the Galgotias Tech Council and upcoming fests. Featuring a human-like avatar, Millie interacts through voice—answering questions and providing responses—while users can also communicate with her by speaking. For accessibility, captions are provided alongside her voice responses.

The project is built with a ReactJS frontend and a TypeScript backend, ensuring a smooth and engaging user experience. Millie is containerized using Docker Compose, making it easy to set up and deploy. 

## 🔧Features
⦁ **Query Handling**:
Millie is capable of answering a wide range of general queries while also providing information about Galgotias Tech Council and upcoming events at Galgotias University.

⦁ **Voice and Text Interaction**:
Millie enables users to ask questions and receive answers through both voice and text, offering a seamless and interactive experience

⦁ **Captions for Accessibility**:
Along with voice responses, Millie provides captions, ensuring accessibility for all users, including those who prefer visual support.

⦁ **Human Avatar**:
Millie features a human-like avatar that provides a more engaging and lifelike interaction, making the conversation feel more natural.
## 🚀 Unique Features
⦁ **Two-Way Voice Interaction**:
Millie allows both users and the avatar to engage in conversational voice exchanges, offering a hands-free, dynamic experience.

⦁ **Real-Time Event Updates**:
Millie provides instant information on upcoming events and activities at Galgotias University, ensuring users are always up-to-date.

⦁ **Human-Like Avatar**:
With a realistic human avatar, Millie enhances user interaction, making conversations more engaging and natural
## 📊 Steps to Set Up
1. Replace `GEMINI_API_KEY` with your own key in the `docker-compose.yml` file.
2. Run the following command:
   ```bash
   sudo docker-compose up -d
   ```
3. Wait for the TTS container to start the web server.

**Important:** Currently, this setup only supports Linux. For Windows, you'll need to host the TTS server manually and adjust some code in the backend.
## 🌍Technology Stack
Technologies used: 

⦁ **3D Models**: Blender, Mixamo

⦁ **Backend**: TypeScript, Express Js

⦁ **Frontend**: React Js, Tailwind CSS, Bun, Vite

⦁ **Technologies**: Docker, Docker Compose, Nginx (as loadbalancer), Ollama, UnSloth (For finetuning), Rhubarb
## 💡Why Millie?
Millie stands out as the ideal choice because it combines real-time information, voice interaction, and a human-like avatar, creating a more engaging and efficient user experience. Unlike traditional text-based assistants, Millie offers multifaceted accessibility, allowing users to interact through both voice and text while also providing captions. Whether for university-specific details or general inquiries, Millie ensures quick, accurate responses, making it the preferred assistant for an enhanced, dynamic experience.
## 🌌Futuristic Approach
⦁ **Multilingual Support**:
Introduce multilingual capabilities to cater to a broader audience, starting with Hindi and other regional languages.

⦁ **Robotic Avatar**:
Upgrade Millie's human-like avatar to a robotic version for a more futuristic and professional look.

⦁ **Expanded Knowledge Base**:
Broaden Millie's knowledge to include a wider range of topics, making it an even more versatile assistant
## 📸 Snapshots
![image](https://github.com/appledog632/ai_avatar_unoff/blob/main/image1.png)
![image](https://github.com/appledog632/ai_avatar_unoff/blob/main/image2.png)

## System Design
![image](https://github.com/appledog632/ai_avatar_unoff/blob/main/systemdesign.png)


