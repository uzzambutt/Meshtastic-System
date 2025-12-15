# Meshtastic Router + Client Devices – Decentralized Mesh Network

## Overview
This project is a decentralized, encrypted mesh communication network built using Meshtastic nodes (ESP32 + LoRa) and Relayers. This network allows off-grid messaging without depending on the internet, cellular towers, or centralized servers.

## What I Built
Multiple nodes configured as:
```
1: Client nodes (paired with phones)
2: Router / relayer nodes (always-on mesh repeaters)
3: A working mesh network capable of multi-hop message routing
4: End-to-end encrypted communication between users
```
## How It Works
```
1: User writes a message in the Meshtastic mobile app
2: Message is encrypted (AES-256-CTR) on the client
3: Encrypted data is sent via LoRa signals to a nearby device
4: Node transmits the message over LoRa radio
5: Other nodes receive and relay the message
6: Destination node forwards it to the recipient phone
7: Message is decrypted and displayed
```
## Hardware Used
ESP32-based Meshtastic-compatible boards (Heltec V3)
LoRa radios (868MHz EU ISM band)
Mobile phones (Android / iOS)

## Images / Demo
![img](https://github.com/uzzambutt/Meshtastic-System/blob/main/src/IMG-20251009-WA0009.jpeg)
![img](https://github.com/uzzambutt/Meshtastic-System/blob/main/src/IMG_20250612_195436.jpg)
![img](https://github.com/uzzambutt/Meshtastic-System/blob/main/src/IMG_20250612_195443.jpg)
![img](https://github.com/uzzambutt/Meshtastic-System/blob/main/src/IMG_20250612_195443.jpg)
![img](https://github.com/uzzambutt/Meshtastic-System/blob/main/src/IMG_20250612_195459.jpg)
![img](https://github.com/uzzambutt/Meshtastic-System/blob/main/src/IMG_20250616_193918.jpg)
![img](https://github.com/uzzambutt/Meshtastic-System/blob/main/src/IMG_20250621_164234.jpg)
![img](https://github.com/uzzambutt/Meshtastic-System/blob/main/src/IMG_20250621_164805.jpg)


## Journal
All journal entries with images and explanation are present on my blueprint profile.

[Meshtastic System](https://blueprint.hackclub.com/projects/2504)


---

Made by Uzzam for Blueprint
