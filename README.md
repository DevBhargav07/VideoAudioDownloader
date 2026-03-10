Download Video using Flask + Python

This project allows users to download  videos or audio using a
Flask web application. It uses the pytubefix package to handle
downloading.

  -------------------
  1. Install Python
  -------------------

Install Python 3.8 or later.

Check if Python is installed:

python –version or python3 –version

If a version number appears, Python is installed successfully.

  ----------------------
  2. Clone the Project
  ----------------------

Clone the repository to your local machine:

git clone https://github.com/DevBhargav07/VideoAudioDownloader.git

Move into the project directory:

cd VideoAudioDownloader

  ---------------------------------
  3. Create a Virtual Environment
  ---------------------------------

A virtual environment keeps project dependencies isolated.

  ---------------
  Windows Setup
  ---------------

Create virtual environment:

python -m venv env

Activate virtual environment:

.env

If activated successfully you will see:

(env) C:>

  ----------------------
  Ubuntu / macOS Setup
  ----------------------

Create virtual environment:

python3 -m venv env

Activate virtual environment:

source env/bin/activate

After activation you will see:

(env) user@system:project$

  ---------------------------------
  4. Install Project Dependencies
  ---------------------------------

Install required packages:

pip install -r requirements.txt

This installs all dependencies needed for the project.

  ------------------------
  5. Run the Application
  ------------------------

Start the Flask application:

python app.py

or on Linux/macOS:

python3 app.py

  -------------------------
  6. Open the Application
  -------------------------

Open your browser and go to:

http://127.0.0.1:5555

You will see the Downloader interface.

  ------------------
  Project Features
  ------------------

• Download videos • Download audio • Simple URL input
interface • User-friendly download notifications

  -------------------
  Technologies Used
  -------------------

Flask Used to create the web application and handle routes.

pytubefix Handles downloading of video and audio streams.

os module Used to dynamically determine the base directory and manage
file paths.

Flash messages (Flask) Used to display notifications to users.

  ---------------
  Download Flow
  ---------------

1.  User enters an URL
2.  Flask processes the request
3.  pytubefix extracts video/audio streams
4.  Selected stream is downloaded to the configured directory
5.  File is delivered to the user

  ---------------------
  Note about Captions
  ---------------------

Handling captions from can be tricky. Currently captions are not
fully implemented.

Possible future approaches: • Download captions separately • Provide a
second input for captions • Use the transcript API

  -----------------
  Project Purpose
  -----------------

This project was built while learning Flask with Python.

It demonstrates: • Flask routing • Handling user input • File
downloading • Integrating external libraries • Providing meaningful
notifications to users

WARNING: DOWNLOADING COPYRIGHTED MATERIAL IS HIGHLY ILLEGAL! I DO NOT TAKE ANY RESPONSIBILITY FOR YOUR USAGE OF THIS TOOL! THIS IS FOR EDUCATIONAL PURPOSES ONLY!
