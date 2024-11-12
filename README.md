# **ESP32_GEMINI Chatbot**  
🤖 **Your AI-Powered Chatbot on the ESP32** 🌐

Welcome to the **ESP32_GEMINI Chatbot** project! With this project, you can connect your ESP32 development board to Wi-Fi, ask questions, and get AI-powered responses using the **Gemini API**. Whether you're building a personal assistant or just curious about how AI can interact with hardware, this project is a fun way to get started!

---

## 🚀 **Project Overview**  
This simple yet powerful project allows you to interact with the **Gemini API** through your ESP32. You type a question in the Serial Monitor, the ESP32 sends it over to the Gemini API, and the answer comes back to you in a blink!  

---

## ⚙️ **Hardware Requirements**  
You'll need the following hardware to get started:

- **ESP32 Development Board**  
  (any model, such as ESP32 DevKit V1, will work)
  
- **Micro USB Cable**  
  (for powering the ESP32 and uploading the code)

- **Wi-Fi Network**  
  (to connect your ESP32 to the internet)

---

## 💻 **Software Requirements**  
To get your code up and running, you'll need to have the following installed:

- **Arduino IDE**  
  (Get it from [here](https://www.arduino.cc/en/software))

- **ESP32 Board Support in Arduino IDE**  
  Follow the instructions [here](https://github.com/espressif/arduino-esp32) to add ESP32 support to your IDE.

---

## 📚 **Libraries Required**  
Make sure to install these libraries in the Arduino IDE:

1. **WiFi.h**  
   For managing the Wi-Fi connection.

2. **HTTPClient.h**  
   To make HTTP requests to the Gemini API.

3. **ArduinoJson.h**  
   For parsing the JSON response from the API.

You can easily install these libraries by going to **Sketch > Include Library > Manage Libraries** and searching for them!

---

## 🔑 **API Key**  
To access the Gemini API, you'll need to sign up and get your **Gemini API Key**. Replace `Gemini_Token` in the code with your own API key. This ensures that your requests are authenticated and processed by the Gemini service.

---

## 🖥️ **Code Breakdown**  

Here’s how the code works step-by-step:

1. **Wi-Fi Connection**:  
   The ESP32 connects to your Wi-Fi network. You'll need to specify your Wi-Fi credentials (SSID and Password) in the code.

2. **User Input**:  
   Once connected, the program will prompt you in the Serial Monitor:  
   `"Ask your Question:"`  
   Simply type your question and hit enter.

3. **API Request**:  
   The ESP32 sends your question as a POST request to the **Gemini API**, carrying your API key for authentication.

4. **AI Response**:  
   The Gemini API processes your question and sends a response back, which the ESP32 parses and displays in the Serial Monitor. It's that simple!

---

## 🔍 **Expected Output**  

**Prompt:**  
_"Ask your Question:"_

**User Input:**  
Your question typed into the Serial Monitor.

**AI Response:**  
The Gemini-powered answer, displayed on the screen.

 

