# AutoTeamsAttender

**AutoTeamsAttender** is a Python automation script that joins and leaves Microsoft Teams meetings based on a predefined schedule. It uses Selenium to interact with the web interface, making online class attendance effortless.

## Features

- 📌 **Automated Attendance** – Joins and exits MS Teams meetings on schedule.
- ⚡ **Python & Selenium** – Uses Selenium WebDriver for browser automation.
- 📅 **Custom Timetable** – Reads a user-defined schedule to manage class timings.
- 🔧 **Flexible & Customizable** – Easily adaptable for different schedules and use cases.

## Requirements

- Python 3.x
- Selenium
- Chrome WebDriver

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AutoTeamsAttender.git
   cd AutoTeamsAttender
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download and place the Chrome WebDriver in the project directory.

## Usage

1. Edit `config.json` to set up your MS Teams credentials and class schedule.
2. Run the script:
   ```bash
   python attender.py
   ```
3. The script will automatically join and leave meetings as per the timetable.

## Contributing

Feel free to submit issues and pull requests to improve AutoTeamsAttender!



