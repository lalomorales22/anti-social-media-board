# Rad Message Board
![Screenshot 2024-09-17 at 11 26 46 PM](https://github.com/user-attachments/assets/b4f40eb8-26bf-4506-bc11-162a51d98e67)

Rad Message Board is a Flask-based web application that allows users to post messages, generate images and videos, and interact with other users' posts. It features user authentication, real-time updates, and integration with AI-powered image and video generation services.

## Features

<p align="center">
  <img src="https://github.com/user-attachments/assets/d47e7d62-ec72-4ede-9339-36a6c6fb5cf8" alt="Screenshot 1" width="200"/>
  <img src="https://github.com/user-attachments/assets/f54bc516-65b1-4644-8006-3087bafbf79b" alt="Screenshot 2" width="200"/>
  <img src="https://github.com/user-attachments/assets/dfc4397e-5355-4d7a-b046-c3e571c553c4" alt="Screenshot 3" width="200"/>
</p>

- User registration and authentication
- Posting messages with text, generated images, and generated videos
- Commenting on messages
- Adding reactions to messages
- Tagging system for messages
- User profiles
- Real-time updates using Socket.IO
- Integration with Stability AI for image generation
- Integration with Luma AI for video generation


## Requirements

- Python 3.7+
- Flask
- Flask-SocketIO
- python-dotenv
- requests
- Pillow
- sqlite3

For a complete list of requirements, see `requirements.txt`.

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/lalomorales22/rad-message-board.git
   cd rad-message-board
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Set up your environment variables:
   Create a `.env` file in the project root and add your API keys:
   ```
   STABILITY_API_KEY=your_stability_api_key_here
   LUMAAI_API_KEY=your_luma_ai_api_key_here
   ```

6. Run the application:
   ```
   python app.py
   ```

7. Open your web browser and navigate to `http://localhost:5000` to use the application.

## Usage

- Register a new account or log in with an existing one.
- Post messages using the form on the home page. You can include text, generate an image, or generate a video.
- Click on tags to view messages with specific tags.
- React to messages using the reaction buttons.
- Comment on messages using the comment form below each message.
- View your profile to see all your posted messages.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
