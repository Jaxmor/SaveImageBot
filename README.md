# StoreBot
This is code for a discord bot I made for a server that stores discord message attachments into the users computer.
This bot exclusively saved images, however it's been changed to save the original file format found in the discord message including .jpg, .png, .gif, and .mp4.
Using the command '!save', the bot will download all attachments in chronological order from the text channel where the command was called from.
Files are saved from oldest message to newest message inside a newly created folder in the current working directory. The folder name matches the text
channel's name and each file shares that name plus an index starting from one.

All python code was written in VS Code.<p>
Python Version: Python 3.12.6<p>
<br>
Credit:
https://www.youtube.com/watch?v=pgmUBOV3IIs

I based my code off of this video, but instead of saving an image the user sends, it saves all previous files found in the text channel.

**Goals**
1. Create a database to store the saved files.
2. Create a website that allows the user to navigate through the database and display the files.

**Known Issues**
1. The bot saves all files correctly into a new folder, however if the user enters the save command again, the bot won't save any new
files submitted after the first save command prompt. A temporary workaround is to delete the old folder and run the save command
again, then all files should be saved in the new folder. Issue maybe caused by the bot not acknowledging already existing files.
