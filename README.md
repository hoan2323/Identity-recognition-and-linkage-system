Identity-recognition-and-linkage-system
📌 Overview
This project implements a smart face recognition system that integrates with Vietnamese National ID (CCCD). The system allows you to:

Extract information from CCCD images (OCR)

Record the corresponding person's face and store it

Re-identify that person if it appears in the camera later

Display the CCCD information of the identified person

This system is suitable for applications such as: smart attendance, access management, paperless identity verification, or blacklist checking system.



Planned upgrade: Face Anti-Spoofing
The system will be expanded to detect and prevent forms of face spoofing, such as:
- Still image attacks (printing photos, holding them in front of webcam)
- Video attacks (opening videos on phones/laptops to fool the camera)
  
Objectives:
- Ensuring that the recognized face is a real face, present in front of the camera
- Preventing logins or identity authentication using fake images/videos
  
Tentatively applied techniques:
- Using CNN models to distinguish real and fake images
