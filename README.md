**Project**


-----
**Components:**
1. Raspberry Pi 4 B
2. Internet Connection
3. Camera Module v2

**Libraries:**
  * OpenCV
  * x264, libcurl
  * libmosquitto
  * FFmpeg
  * C Standard Library (libc)

**The Flow**:
1. Start Camera recording.
2. Stream Video in real-time.
3. Create a Web Server to make the stream available to others.
4. Apply Motion-Detection Algorithm to detect any movements from the stream.
5. Send alert on Telegram Channel if movement detected.
6. Publish Message to MQTT Broker if movement detected.


**Video Stream**
