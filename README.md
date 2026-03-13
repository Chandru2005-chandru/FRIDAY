# FRIDAY LiveKit Agent 🎤

Welcome to the FRIDAY LiveKit agent! This project allows you to use real-time voice features via the LiveKit platform.

## Setup 🛠️
1. Create a Python virtual environment:
   ```bash
   python -m venv venv
   ```
2. Activate the virtual environment:
   - For Windows:
     ```bash
     venv\Scripts\activate
     ```
   - For Mac/Linux:
     ```bash
     source venv/bin/activate
     ```
3. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Environment Variables 🌍
Make sure to set the following environment variables:
- `LIVEKIT_URL` - Your LiveKit URL
- `LIVEKIT_API_KEY` - Your LiveKit API Key
- `LIVEKIT_API_SECRET` - Your LiveKit API Secret
- `GOOGLE_API_KEY` - Your Google API Key
- `GMAIL_USER` - Your Gmail User
- `GMAIL_APP_PASSWORD` - Your Gmail App Password

## Running the Agent ▶️
To run the agent, execute the following command:
```bash
python agent.py
```

## Features ✨
- **Real-time voice** via LiveKit
- **Google real-time model voice** Aoede
- **Weather updates** via [wttr.in](http://wttr.in)
- **Web searches** via [DuckDuckGo](https://duckduckgo.com)
- **Email sending** capabilities

Make sure to check out the example environment configuration file, `.env.example`, for guidance on how to set up your environment variables!