# SaveImageBot
This is code for a discord bot I made for a server that saves attachments.
This bot exclusively saved images, however it has been changed to save the original file format found in discord including .mp4, .gif, .png, and .jpg.
Using the command '!save', the bot will download all attachments in chronological order from the text channel where the command was called from.
Files are saved from oldest message to newest message inside a newly created folder in the current working directory. The folder name matches the text
channel's name and each file shares that name plus an index starting from one.

All python code was written in VS Code.<p>
Python Version: Python 3.12.6<p>
<br>
Credit:
https://www.youtube.com/watch?v=pgmUBOV3IIs

I based my code off of this video, but instead of saving an image the user sends, it saves all previous images found in the text channel

**Goals**
1. Create a database to store these images
2. Create a website that allows the user to navigate through the database and display the image files
