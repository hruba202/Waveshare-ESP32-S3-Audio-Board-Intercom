# Waveshare ESP32-S3 Audio Board Intercom

ESPHome configuration for the **Waveshare ESP32-S3-AUDIO-Board** with a camera and an external **ST7789 240×240 SPI display**.

Features:
- Two-way audio calls using VoIP Stack.
- Remote contact’s camera snapshots displayed through Home Assistant.
- Physical buttons for calling, answering, selecting contacts and hanging up.
- Automatic camera preview recovery after temporary connection failures.
- Microphone mute and volume controls in Home Assistant.

Camera, display and ESP-to-ESP audio have been tested. The latest automatic preview recovery changes compile successfully and still need hardware verification. The display uses periodically refreshed snapshots, not continuous video.

Keep the YAML, helper headers, audio file and `intercom_components` folder together. Configure credentials in your own `secrets.yaml`; never upload secrets to GitHub.

Built with assistance from **OpenAI Codex**, using ESPHome and the VoIP/Audio Stack components by **n-IA-hane**. Upstream licenses and source information are included.


<img width="3024" height="4032" alt="cama" src="https://github.com/user-attachments/assets/ca0c0c3b-5401-4a8d-b83c-34a511c90b33" />
<img width="4032" height="3024" alt="IMG_2447" src="https://github.com/user-attachments/assets/d66776c3-8291-4cb4-9717-af0b8d252e56" />


