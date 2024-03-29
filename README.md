# Chat Web App

A real-time web-based chat application built with Python, Flask, and Socket.IO.

## Features

- Real-time messaging
- Multiple chat rooms
- User authentication
- Responsive design

## Installation

1. Ensure you have Python 3.9 or later installed on your system.

2. Clone this repository:

   ````bash
   git clone https://github.com/JamesMathenge/Web-Chat-App

3. Navigate to the project directory
    cd Chat-Web-App

4.  Create and activate a virtual environment (recommended):
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`

5. Install the required dependencies:
    pip install -r requirements.txt

## Usage
## Running the Server

1. Navigate to the website directory:
    cd website

2. Start the Flask server:
    python main.py

3. Open your web browser and visit http://localhost:5000 to access the chat application.

## Clearing Message History
To clear the chat message history, simply delete the messages.db file from the project directory.

## Outdated Message Server
Before using Socket.IO for real-time messaging, a custom message server was implemented using standard Python sockets. The code for this implementation is located in the old_msg_server/ directory. However, this implementation is no longer being actively maintained or used in the current version of the application.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.