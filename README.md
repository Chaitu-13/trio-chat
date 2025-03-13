# Triochat
**_Chat app_**

## Features & Functionality:
- Real-time messaging for sending and receiving messages
- Built using Flask with Socket.IO for real-time communication
- Messages from both the sender and receiver are stored in an SQLite3 database via Flask-SQLAlchemy
- User account creation and management functionality
- Session management through login authentication
- Backend built entirely with Flask for handling chat operations
- Frontend UI is simple and built with HTML, CSS, and JavaScript, utilizing jQuery for Socket.IO integration and other dynamic features

## Local Setup
```sh
# Clone the repo
git clone https://github.com/Chaitu-13/trio-chat

# Goto Cloned Directory
cd trio-chat

# Run Python Virtual
python3 -m venv .

# Activate the Virtual
source bin/activate

# Install Requirements
pip install -r requirements.txt

# Run the app.py
python server.py
```

## Routes
- Main Route Link - http://127.0.0.1:5000/ - interface of homepage if logged in state else in login state page
- Account - https://127.0.0.1:5000/register - Account Creation
- New Chat - https://127.0.0.1:5000/new-chat - Menu of members list for chatting to member by unique msg id
- Chat - https://127.0.0.1:5000/chat/ - Chat Message List of Specific members and its history
- Visualize - https://127.0.0.1:5000/visualize - to get the info of registered memebers via pandas and matplotlib (yet to come)
- Name - https://127.0.0.1:5000/get_name - get the name of user based on login session
- Leave - https://127.0.0.1:5000/leave - logout the chat page
