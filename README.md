# Jupyter-Folium-GPS-Map
Extract GPSinfo from JPG images and display on a map

JPG images must contain EXIF GPSInfo fields

If GPSInfo is missing the image is ignored.

I used this to find out where I took the photos on my hol to Norway back in May 2025 - getting old - memory fades!

set your start location [lat,lon]
```
startLoc= [60.3913, 5.3221] # Bergen, Norway
```

and where to find the pics

```
sourcePath="M:/Camera/pics/*.jpg"
```
You get a result like this. Click on the pins to find the name of the image at that point.

<img width="1012" height="668" alt="image" src="https://github.com/user-attachments/assets/52b165a9-220d-4aac-a45a-5bac5b0c66b8" />
