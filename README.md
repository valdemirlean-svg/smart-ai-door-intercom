# Smart AI Door Intercom

An autonomous, intelligent, and privacy-conscious residential gatekeeper built with Home Assistant, ESPHome and AI.

This project creates a fully autonomous residential intercom system capable of interacting with visitors and delivery drivers, understanding intent, and managing notifications for residents.

The system prioritizes privacy and security and will **never reveal whether residents are home**.

## Key Features

- Autonomous AI interaction with visitors and delivery drivers
- Privacy-first design that prevents social engineering
- Smart delivery management when nobody is home
- Internal voice announcements inside the house
- Resident access via NFC tags or facial recognition
- Offline fallback mode when internet is unavailable
- Do Not Disturb schedule during night hours

## Hardware

### External Unit (Gate)

- ESP32-S3 Zero
- LD2410C mmWave radar
- INMP441 I2S microphone
- PCM5102A DAC
- Passive NFC Tag
- PAM8406 amplifier
- Speaker 3W / 4Ω / 35mm
- Illuminated metal push button
- RTSP camera
- USB wall outlet module 5V / 2A

### Internal Unit (Announcements)

- Home Assistant host PC
- USB sound card
- Desktop speakers
