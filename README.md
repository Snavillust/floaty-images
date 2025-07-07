# floaty-images

A simple HTML bounce/float script for Twitch streaming.  
This project adds floating, bouncing images to your stream using a transparent HTML canvas.  
It's designed for OBS browser sources and supports emotes, caricatures, or any PNG images you want to float around your screen.

---

##  Setup

Create a folder like this and place your `.html` and `.png` files inside:

floaty-caricatures/

├── floating.html ← main HTML file

├── img1.png ← your image

├── img2.png ← another one

├── img3.png ← and so on


---

## 🧠 Edit the HTML

Open `floating.html` and scroll to around **line 22**. Update the image list like so:

```html
<script>
  const imagesToLoad = [
    'img1.png',
    'img2.png',
    'img3.png'
  ];
</script>
```

Using in OBS

Open OBS

Add a Browser Source

Check “Local File”

Select your floating.html file

Set resolution (e.g. 1920x1080)
