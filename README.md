# Meshtastic Router + Client Devices – Decentralized Mesh Network

## Overview
This project demonstrates a decentralized, encrypted mesh communication network built using Meshtastic nodes (ESP32 + LoRa) and mobile clients. The system enables off-grid messaging without relying on the internet, cellular towers, or centralized servers.

## What I Built
Multiple Meshtastic nodes configured as:
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
All images and demos are present in /src folded.

## Journal
All journal entries with images and explanation are present on my blueprint profile.

[Meshtastic System](https://blueprint.hackclub.com/projects/2504)


---

Made by Uzzam for Blueprint
