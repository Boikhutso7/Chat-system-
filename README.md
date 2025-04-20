
Real-Time Multi-User Chat Application

A Python-based chat system with both command-line interface (CLI) and graphical user interface (GUI) options, supporting real-time messaging for multiple users.
Features

    Real-Time Messaging: Instant message delivery between connected users

    Multi-User Support: Handle multiple simultaneous connections

    Dual Interface: Choose between CLI or GUI based on preference

    Username Management: Unique identifiers for each chat participant

    Message Broadcasting: Send messages to all connected users

    Disconnect Handling: Graceful connection termination notifications

    Notification Sounds: Audible alerts for new messages (GUI version)

    Cross-Platform: Works on Windows, macOS, and Linux systems

Technologies Used

    Python 3.x

    Socket programming for network communication

    Threading for concurrent connections

    Tkinter for GUI interface

    Sound effects (optional for GUI version)

Installation

    Clone the repository:

git clone https://github.com/Boikhutso7/chat-system.git
cd chat-system

Install required dependencies:

    pip install -r requirements.txt

Usage
Server

Start the chat server:

python server.py

Clients

For CLI interface:

python client_cli.py

For GUI interface:

python client_gui.py


  
