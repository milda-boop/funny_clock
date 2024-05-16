# Funny Clock
A clock displayed on the waveshare screen for raspberry pi pico..... with something not quite right.

# Hardware used
- Waveshare Pico LCD 1.3
- Raspberry Pi Pico W board

# Libraries used
[Drive code](https://github.com/milda-boop/funny_clock/blob/main/funnyclock.py#L7-L346) borrowed from [Instructables](https://www.instructables.com/WS-Pico-13-IPS-LCD-240x240-Display-Workout/)

# Description
A simple, normally functioning clock, or is it? Upon closer inspection, it can be seen that the duration of each second is a little bit different. This clock has been designed in a way where each 'second' is actually a random value between 0.5 and 1.5. All 60 values add up to 60, and so can go unnoticed.

To develop this project further, I would have retrieved the current time from the internet so the time matches up correctly. For this project, the time starts at 00:00:00.

# Links
[Video of the working application](https://youtu.be/LDhBbMJojkI)
