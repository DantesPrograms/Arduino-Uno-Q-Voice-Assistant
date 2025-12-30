# Uno Q Voice Assistant (Headless Edition)

A pure hardware voice assistant running on the **Arduino Uno Q**. It uses the Qualcomm Dragonwing processor for AI logic and the STM32 for hardware control. No web server, no screens—just voice.

## 🔌 Hardware Mapping
| Component | Pin | Function |
| :--- | :--- | :--- |
| **Blue LED Strip** | D2 | Visual Feedback (Thinking/Speaking) |
| **Button (Up)** | D3 | Volume Up / Action A |
| **Button (Down)** | D4 | Volume Down / Action B |
| **USB Audio** | USB | Mic Input & Speaker Output |

## ⚡ Power Requirements
* **Peak Power:** ~10.25W
* **Required PSU:** 5V / 3A USB-C Adapter.

## 🚀 Usage
1.  **Hardware:** Flash `sketch.ino` to the Uno Q.
2.  **Software:** Install dependencies: `pip install -r requirements.txt`.
3.  **Config:** Add your Google Gemini API Key in `python/main.py`.
4.  **Run:** Execute `python python/main.py`.
5.  **Speak:** Say **"Hey Uno"** to trigger the assistant.
