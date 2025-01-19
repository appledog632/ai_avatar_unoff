# Millie-AI

Millie is an AI-powered chatbot designed specifically for university environments, with a focus on providing information related to the Galgotias Tech Council and upcoming fests. Featuring a human-like avatar, Millie interacts through voice—answering questions and providing responses—while users can also communicate with her by speaking. For accessibility, captions are provided alongside her voice responses.

The project is built with a ReactJS frontend and a TypeScript backend, ensuring a smooth and engaging user experience. Millie is containerized using Docker Compose, making it easy to set up and deploy. Just replace the GEMINI_API_KEY in the docker-compose.yml file, and you're good to go.

## Steps to Set Up
1. Replace `GEMINI_API_KEY` with your own key in the `docker-compose.yml` file.
2. Run the following command:
   ```bash
   sudo docker-compose up -d
   ```
3. Wait for the TTS container to start the web server.

> **Important:** Currently, this setup only supports Linux. For Windows, you'll need to host the TTS server manually and adjust some code in the backend.

## Audio and Lip-Sync Tools
This project uses:
- [Coqui TTS](https://github.com/coqui-ai/TTS) for generating audio responses.
- [Rhubarb Lip Sync](https://github.com/DanielSWolf/rhubarb-lip-sync) for creating lip-sync animations to match audio output.

## Acknowledgments
Special thanks to the contributors who supported this project:
- [NixSkye](https://github.com/NixSkye)
- [appledog632](https://github.com/appledog632)

