# Face Recognition with Real Time

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT

## Description

This project implements face recognition with real-time capabilities using python, Opencv. It utilizes Python 3.7, higherOpenCV, cvzone, numpy, face_recognition, Firebase Admin SDK to achieve accurate and efficient face recognition in real-time scenarios.

![0](https://github.com/amithhd/Face_Recognition_With_Real_Time/assets/103755649/29f06475-9f35-45aa-8eb2-7001edd022d7)

## Requirements

- PC or Laptop
- Web Cam
- Python 3.7 or higher
- windows or linux
- Visual Studio
- Firebase Account
- Internet

## Sample Output

<h1 align="center"><img width="660" alt="1" src="https://github.com/amithhd/Face_Recognition_With_Real_Time/assets/103755649/cb6cca6b-142a-4666-a9b5-1dd64c9f5aa5"></h1>

<h1 align="center"><img width="660" alt="2" src="https://github.com/amithhd/Face_Recognition_With_Real_Time/assets/103755649/46158c52-e7f6-490d-b56f-93f3d634d0a6"></h1>

<h1 align="center"><img width="660" alt="3" src="https://github.com/amithhd/Face_Recognition_With_Real_Time/assets/103755649/47c175af-8489-4c90-ae62-88f243ecb980"></h1>

<h1 align="center"><img width="660" alt="4" src="https://github.com/amithhd/Face_Recognition_With_Real_Time/assets/103755649/c05b0d05-ea18-4a3f-a227-1608d8ccf46a"></h1>

## GIF Out Sample

<p align="center">
    <img width="660" src="https://github.com/amithhd/Face_Recognition_With_Real_Time/assets/103755649/2dffd5b9-1b9d-498c-a4cb-450cec215a81" alt="sample1">
</p>

<p align="center">
    <img width="660" src="https://github.com/amithhd/Face_Recognition_With_Real_Time/assets/103755649/5a2973fb-826f-473a-9c62-dcd62584f25a" alt="sample1">
</p>

## Real Time Database

Developing a real-time face recognition system involves integrating cutting-edge facial recognition algorithms with a live camera feed. By establishing a seamless connection to a Firebase real-time database, the system can dynamically upload scanned faces, ensuring efficient storage in the database along with simultaneous attendance updates. As individuals are recognized in real-time, their corresponding photos are stored securely in Firebase storage, providing a comprehensive solution for accurate attendance tracking. This innovative system ensures that face recognition, database interaction, and attendance updates occur seamlessly and concurrently, enhancing efficiency and reliability in various applications.

Implementing real-time face recognition involves integrating a system that seamlessly connects with a live database, such as Firebase. As faces are scanned in real time, the captured images are instantly uploaded to the Firebase database, ensuring a swift and efficient storage process. Concurrently, the attendance records are dynamically updated in real time whenever a face is successfully detected. This automated synchronization between face detection and database updates ensures a seamless and immediate reflection of attendance changes. Overall, this solution provide a robust and efficient mechanism for real-time face recognition with instant updates to the connected Firebase database, facilitating a streamlined and effective attendance management system.

<h1 align="center"><img width="660" alt="database" src="https://github.com/amithhd/Face_Recognition_With_Real_Time/assets/103755649/489f48c3-738b-42a7-a22a-6a0f17290668"></h1>

## Installation

### Requirements

  * Python 3.3+ or Python 2.7
  * macOS or Linux (Windows not officially supported, but might work)

### Installation Options:

#### Installing on Mac or Linux

First, make sure you have already installed with Python :

  * [How to install dlib from source on macOS or Ubuntu](https://gist.github.com/ageitgey/629d75c1baac34dfa5ca2a1928a7aeaf)

Second, make sure you to install the PyCharm:

  * PyCharm Download Link ===>> [click here](https://www.jetbrains.com/pycharm/download/?section=windows)
  
Then, make sure you have cmake installed:  
 
```brew install cmake```

Finally, install this module from pypi using `pip3` (or `pip2` for Python 2):

```bash
pip3 install face_recognition
```

## Future Plan

The future plan is to improve the recognition rate when there are unintentional changes in a person like tonsuring head, using scarf, beard. The barcode of a particular subject will be displayed on the projector which will change every 10 seconds to avoid proxy attendance. The student needs to scan the barcode and capture the photo within 10 seconds or the barcode will expire. This will prevent other students from capturing the photo of barcode and sending it to their colleagues to mark the attendance.
