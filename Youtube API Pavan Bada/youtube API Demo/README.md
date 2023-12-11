
This is a simple video playback application that allows you to watch unlisted YouTube videos using the YouTube V3 API and a custom video player.

Features:

Fetch unlisted YouTube videos using video ID.
Display video in a custom video player.
Customizable player controls and video size.
Requirements:

Python 3.x
Flask
youtube_data_api
Instructions:

Install dependencies:

Bash
pip install flask youtube_data_api
Use code with caution. Learn more
Get your API key:

Create or use an existing Google Cloud project.
Enable the YouTube Data API v3.
Create API credentials and download the JSON file.
Configure the application:

Open app.py in a text editor.
Replace YOUR_API_KEY with the actual API key from your downloaded JSON file.
Run the application:

Bash
python app.py
Use code with caution. Learn more
Open http://localhost:5000/ in your browser.

Enter an unlisted YouTube video ID and click "Play Video".

Customization:

You can customize the application further by modifying the code in app.py and player.html.
You can explore libraries like Plyr to implement custom video controls.
You can add features like playlists and video playback progress tracking.
Important notes:

This application requires permission to access the unlisted YouTube videos.
The provided code is a basic example and can be extended for additional functionalities.
Ensure you have a stable internet connection for smooth playback.
