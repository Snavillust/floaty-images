# floaty-images
A simple HTML bounce/float script for twitch streaming.
This project adds floating, bouncing images to your stream using a transparent HTML canvas. It's designed for OBS browser sources and supports emotes, caricatures, or any PNG images you want to float around your screen.

Setup a Folder and add png's next to the .html
floaty-caricatures/
├── floating.html     ← main HTML file
├── img1.png       ← your image
├── img2.png       ← another one
├── img3.png       ← and so on

Edit the HTML and on Line 22 add in the img's names Like the below example.
<script>
    const imagesToLoad = [
      'img1.png',
      'img2.png',
      'img3.png',

Open OBS
Add a Browser Source
Check “Local File”
Select your floating.html
Set resolution to match your canvas (e.g. 1920x1080)
