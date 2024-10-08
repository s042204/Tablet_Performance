# Tablet Performance Monitor

## Overview

A web-based tool for running optimization scripts on tablets using Flask and ADB. This tool allows users to improve tablet performance by running various scripts and monitoring resource usage through a user-friendly web interface.

## Features

- **Clear Cache**: Quickly clear the cache to free up space and improve performance.
- **Disable Services**: Disable unnecessary services like Bixby and Samsung Notes to reduce resource usage.
- **Limit Background Processes**: Limit the number of background processes to enhance tablet performance.
- **Turn Off Animations**: Turn off window, transition, and animator duration animations to speed up the tablet.
- **Optimize Battery Usage**: Run scripts to optimize battery usage and extend battery life.
- **Set Performance Mode**: Switch the tablet to performance mode for better responsiveness.
- **List Connected Devices**: List all devices connected to the ADB server.
- **Disable Virtual Keyboard**: Disable the virtual keyboard to prevent it from consuming resources.
- **Remote Access to Tablet**: Use scrcpy to remotely control the tablet from a PC.
- **Enable High Performance**: Enable high performance mode for the tablet.
- **Restore Default Settings**: Restore the tablet to its default settings.
- **Check Software Updates**: Check for and manage software updates.
- **Enable Developer Options**: Enable developer options on the tablet.
- **Enable/Disable Wi-Fi**: Toggle Wi-Fi on and off.

## Getting Started

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/tablet-performance-monitor.git
    cd tablet-performance-monitor
    ```

2. **Set up the virtual environment**:
    ```sh
    python -m venv venv
    venv\Scripts\activate
    ```

3. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Run the Flask application**:
    ```sh
    flask run
    ```

5. **Open your browser and navigate to** `http://127.0.0.1:5000`