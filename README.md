# Squalo AI 🦈

![logo](https://github.com/ajsb85/squalo.ai/assets/663460/c03e639b-8106-4a18-9724-87e7c4095699)

The system for detecting and identifying sharks and other marine life and objects is imposing. Its advanced deep neural networks and image processing techniques efficiently distinguish and identify sharks from other targets. It can process dynamic video feeds and analyze static images with great precision. Moreover, the system has an onboard megaphone that provides an overhead warning to swimmers and surfers if a shark or potential risk is detected. This cutting-edge AI system will undoubtedly positively impact the public by making recreational boats and swimming much safer. 

[Ameba Pro 2](https://www.amebaiot.com/en/amebapro2/#rtk_amb82_mini) has the remarkable capabilities to make Squalo AI an advanced technology that incorporates cutting-edge image processing techniques and state-of-the-art image sensors to detect and classify objects. Moreover, they employ deep-learning neural networks to enhance the accuracy and efficiency of this process. The advancements in AI technology are awe-inspiring and hold potential for various applications.

![image](https://github.com/ajsb85/squalo.ai/assets/663460/8e5ed5b7-b35d-4ed8-8595-0f0090ad99cc)

The primary objective of this project is to refine the system's training to recognize great white sharks and hammerhead sharks in challenging conditions, such as murky water or unclear deep-sea conditions.

To address these challenges, an object detection system based on faster regions with convolutional neural networks has been proposed to detect shark species in real-time. The ResNet50 deep architecture serves as the feature extractor for model training. The developed shark detector has demonstrated impressive performance, with average scores of precision (0.82), recall (0.78), and accuracy (0.85) on experimental image and video datasets.

## NMEA2000 Switch bank PGN definitions

### Binary Status Report - PGN 127501 (0x1F20D)

The Squalo AI camera device sends out this PGN; see the table below for the details.

| Signal|Meaning|
|:----|:----|
| Bank Instance|Instance of the message, default value 0|
| Status 1 - Solid State Relay|"On" - The relay on the camera is active, the contact is closed|
| Status 2 - Alarm|"On" - There is an alarm condition that means a shark was detected|
| Status 3 … 28|Not used, reports as "Unavailable"|

### System Startup Sync

Once the Squalo AI system is powered on, the Camera Device will automatically transmit all instances to ensure that any third-party products already in use can sync their data registers with the startup state. This helps ensure a seamless and efficient experience for all users.

## Camera Enclosure Proposal

This is a reference picture for the enclosure

![TIX402-CAM-Angled](https://github.com/ajsb85/squalo.ai/assets/663460/ade02e4b-abb7-4650-836c-4e168a5ac803)

### Ultra-wide, no-distortion lenses

Theia Technologies and their suite of rectilinear lenses offer an ultra-wide field of view without the barrel distortion or loss of edge resolution familiar with fisheye-style lenses. Their patented Linear Optical Technology creates multi-megapixel lenses that offer horizontal lots of view up to 135 degrees with very low distortion, making them ideal for shark detection and providing excellent peripheral vision.

Theia offers a lens calculator that relates the field of view, resolution, and object distance to assist in the selection process. They also provide an image resolution simulator and white papers on their lens technology to help us better understand their products.

## Camera Installation

The N2K network has limited data bandwidth, and therefore, it does not support streaming video content. To connect Squalo AI, we recommend the network cable from Phoenix Contact part number 1407349 that uses the connector M8  (Coding: A / IP67).

To manage your camera's functionality (turn the device on and off), it is supplied with an NMEA 2000 Micro Male connector; the drop cable is not supplied with the device and should be purchased separately. For connection to the Raymarine SeaTalk NG network, use cables with Raymarine part numbers A06045 or A06075.

## Camera Enclosure Maintenance

Maintaining the locking nut securely fastened is imperative; therefore, it is recommended to carry out periodic inspections. We advise a monthly assessment of the camera module and cable connections to ensure their optimal condition. The glass lens can be kept clean using a plastic scraper or a soft brush, while abrasive cloths or cleaning agents should be avoided, as they could inflict irreparable damage to the lens. Furthermore, it is prudent to employ a high-quality antifouling system to coat the external body of the device, thus preventing the accumulation of marine growth and extending its lifespan. Regular coating renewal is necessary to maintain the device in excellent condition.

## Certifications

The Squalio AI camera device will be certified by the National Marine Electronics Association and is designed for operation in an NMEA 2000 network. 

## Academic Support

I am an IEEE Member valued for +15 years and a member of the Oceanic Engineering Society (OES)

### IEEE Oceanic Engineering Society (OES)
OES members are engaged in all aspects of science, engineering, and technology that address research, development, and operations about all bodies of water. Members are encouraged to promote close cooperation and exchange of technical information while fostering technical and professional growth through access to periodicals, conference discounts, and professional networking.

_Per ardua ad mare_

### Marine Technology Society
The Marine Technology Society (MTS) promotes awareness, understanding, and the advancement and application of marine technology.

![MTS-OES-Long-Logos-Vector-Dot 1](https://github.com/ajsb85/squalo.ai/assets/663460/0b848cdd-d06a-426d-af39-e03be40192cd)
