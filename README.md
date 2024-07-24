# Real-Time Audio Data Transmission Application

## Overview

This project is a client-server application developed in C++ for real-time audio data transmission. The application uses Winsock for TCP-based network communication and the Windows Multimedia System for audio capturing and playback, ensuring low-latency and reliable audio streaming over the TCP/IP protocol.

## Features

- **Real-time Audio Transmission**: Captures and transmits audio data in real-time between client and server.
- **TCP Communication**: Utilizes Winsock for reliable TCP communication.
- **Audio Capture and Playback**: Implements Windows Multimedia System for audio capturing and playback.
- **Low-latency Streaming**: Ensures low-latency and reliable audio streaming over TCP/IP.

## Tech Stack

- **Programming Language**: C++
- **Networking**: Winsock (TCP)
- **Audio Processing**: Windows Multimedia System
- **Protocol**: TCP/IP

## Getting Started

### Prerequisites

- Windows operating system
- C++ compiler (e.g., Visual Studio)
- Winsock library
- Windows Multimedia System library

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/DityaChawla/real-time-audio-transmission.git
    ```
2. Open the project in your C++ development environment.

### Usage

1. **Server**:
    - Compile and run the server code.
    - The server will start listening for incoming connections.

2. **Client**:
    - Compile and run the client code.
    - Connect to the server using the server's IP address and port number.
    - The client will start capturing audio data and transmit it to the server.
    - The server will receive and play the audio data in real-time.

### Configuration

- **Server IP and Port**:
    - Update the server IP and port number in the client code to match your server's configuration.

### Code Structure

- **Server Code**:
    - Handles incoming client connections.
    - Receives audio data and plays it in real-time.

- **Client Code**:
    - Captures audio data from the microphone.
    - Transmits the captured audio data to the server.


