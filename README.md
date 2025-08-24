

Python-based YouTube Downloader
This is a simple GUI application for downloading YouTube videos, built using 

CustomTkinter for the user interface and the pytube library for handling the downloads. The program is designed to automatically select and download the highest quality version of the video available.


Features

Simple Interface: A straightforward graphical user interface for easy use.

High-Quality Downloads: Automatically downloads the best possible video quality.

Download Status: A pop-up window shows a "Download successful!" message and the total time taken to download the video.

Error Handling: Displays an error message if an invalid or empty YouTube link is entered.

Organized Output: Creates a folder named youtube_downloads to store all the downloaded videos.

Dependencies

To run this application, you need Python and the following libraries:

pytube: Used for the core video downloading functionality.

CustomTkinter: Used for creating the modern-looking GUI.

Tkinter: This is a standard Python library, so it's likely already installed.

You can install all dependencies from the requirements.txt file by running this command:

Bash
pip install -r requirements.txt
How to Use

From the Python Script

Clone this repository to your local machine.

Run the main script from your terminal:

Bash
python python_youtube_downloader.py
A GUI window will appear. Paste the YouTube video URL into the text box and click the 

Download button.

Once the download is complete, a pop-up window will appear with a success message.

Your video will be saved as an 

.mp4 file inside the youtube_downloads folder.

Using the Executable (.exe)

An executable version of the application is available for Windows users.

Access the executable from the provided Google Drive link.

Navigate to the 

dist folder, and then the python_youtube_downloader folder.

Double-click the 

python_youtube_downloader.exe file to run the application.

Follow the same steps as above to download your video.
