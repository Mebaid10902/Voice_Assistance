# 🗣️ Voice Assistant on Raspberry Pi  
A Raspberry Pi-based voice assistant powered by [Voiceflow](https://www.voiceflow.com/), running local audio input/output and cloud-based logic.

---

## 🔧 Setup Instructions

### 🧱 Hardware Requirements
- Raspberry Pi (or any Python3-compatible system)  
- Microphone & Speaker (or combined headset)  
- Audio input must support **16kHz** sample rate

---

### 📦 System Dependencies  
Install essential system packages:

```bash
sudo apt-get update
sudo apt-get install -y \
    python3 \
    python3-pip \
    python3-all-dev \
    python3-pyaudio \
    portaudio19-dev \
    libsndfile1 \
    mpg123
🐍 Python Dependencies
Install required Python libraries:

bash
Copy
Edit
pip3 install -r requirements.txt
🔐 Voiceflow API Configuration
Set your Voiceflow API key as an environment variable:

bash
Copy
Edit
export VF_API_KEY=your_voiceflow_api_key
📘 You can generate and manage your API key from the Voiceflow Developer Portal.

🚀 Running the Assistant
Start the voice assistant with:

bash
Copy
Edit
python3 ./src/main.py
