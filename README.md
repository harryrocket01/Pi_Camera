# Pi_Camera

Command list to live stream camera data over TCP.

Using RPI 4 running Rasbaian, with a camera module 3 connected.

```
libcamera-vid -t0 --width 1920 --height 1080 --framerate 10 --nopreview --codec h264 --profile high --intra 5 --listen -o tcp://0.0.0.0:8494
```

```
tcp/h264://192.168.100.212:8494
```

