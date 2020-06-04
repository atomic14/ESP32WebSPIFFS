# Introduction

This project demonstrates how to serve content from the ESP32 SPIFFS using AsyncWebServer.

Click the image to watch the demo video.

[![Demo Video](https://img.youtube.com/vi/NVD46mRbVXM/0.jpg)](https://www.youtube.com/watch?v=NVD46mRbVXM)

# Setup

Update the file `wifi_credentials.h` with your SSID and PASSWORD.

```c
#define SSID "YOUR_SSID"
#define PASSWORD "YOUR_PASSWORD"
```

Now just compile and run the sketch.

Once the sketch is running you should be able to use a browser to open the device's UI.

```
http://demo-server.local
```

Push the button and the built in LED should turn off and on.
