# LPU Leave Apply Bot

## Overview
LPU Leave Apply Bot is a Python-based Flask web application that automates the leave application process for LPU students. The bot uses Selenium to interact with the LPU UMS portal and submit leave requests efficiently.

## Features
- Automated login to LPU UMS
- Leave request submission based on leave type
- Pop-up notification handling
- Leave term, reason, and time selection
- Secure credential input via web form

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/LPU-Leave-Bot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd LPU-Leave-Bot
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Ensure you have the latest version of Firefox and `geckodriver` installed.

## Usage
1. Start the Flask server:
   ```bash
   python app.py
   ```
2. Open your browser and go to:
   ```
   http://127.0.0.1:9001
   ```
3. Enter your LPU UMS credentials and leave details, then submit.

## Configuration
- Modify the `config.json` file (if applicable) to set default leave options.
- Adjust Selenium configurations to match your browser setup.

## Contributing
Feel free to fork this repository and submit pull requests with improvements or new features.

