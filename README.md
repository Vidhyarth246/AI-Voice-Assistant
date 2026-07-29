# AI-Voice-Assistant
the project is based on the voice assistant . It also control home automation .
# Aura AI Voice Assistant (ESP32)

Aura is an AI-powered voice assistant built using the ESP32. It records voice commands, converts speech to text using Deepgram, generates intelligent responses with Google's Gemini AI, and replies using Text-to-Speech. The assistant can also control IoT devices such as lights and fans using voice commands.

---

## Features

- 🎤 Voice recording using ESP32
- 🗣 Speech-to-Text with Deepgram
- 🤖 AI responses using Google Gemini 1.5 Flash
- 🔊 Text-to-Speech playback
- 💡 Voice-controlled Light
- 🌪 Voice-controlled Fan
- 📡 Wi-Fi connectivity
- 💾 SD Card audio recording
- 🔁 Repeat last AI response
- 🌈 RGB status LEDs
- 🔋 Battery voltage monitoring

---

## Hardware Used

- ESP32 Development Board
- Microphone (I2S)
- Speaker
- SD Card Module
- LEDs
- Push Button
- Repeat Button
- Relay Module
- Light
  

---

## Software & Libraries

- Arduino IDE
- WiFi.h
- WiFiClientSecure.h
- ArduinoJson
- Audio.h
- SD.h
- SimpleTimer

---

## APIs Used

- Deepgram Speech-to-Text API
- Google Gemini 1.5 Flash API
- Google Text-to-Speech

---

## Voice Commands

### Device Control

- Turn on switch 1
- Turn off switch 1
- Turn on switch 2
- Turn off switch 2


## Project Workflow

1. User presses the record button.
2. ESP32 records audio.
3. Audio is saved to the SD card.
4. Deepgram converts speech into text.
5. Gemini AI generates a response.
6. Google TTS converts the response into speech.
7. ESP32 plays the response through the speaker.
8. Voice commands can control connected appliances.

---

---

## Installation

1. Clone this repository

```bash
git clone https://github.com/yourusername/Aura-AI-Voice-Assistant.git
```

2. Open the project in Arduino IDE.

3. Install the required libraries.

4. Add your credentials:

- Wi-Fi SSID
- Wi-Fi Password
- Gemini API Key
- Deepgram API Key

5. Upload the code to your ESP32.

---

## Future Improvements

- Face Recognition
- OLED Display Interface
- Smart Home Automation
- Weather Information
- Home Assistant Integration


---

## Author

Vidhyarth Vyas

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- Google Gemini API
- Deepgram
- Arduino Community
- ESP32 Community
