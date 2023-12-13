# Tello Position Control

## Set AP Mode on Tello

> From https://tello.oneoffcoder.com/swarm.html#set-tello-modes

Each Tello Edu can exist in AP Mode or Station Mode.

- AP Mode or Access Point Mode is when the Tello becomes a client to a router.
- Station Mode is when the Tello acts like a router.

Only when a Tello Edu is set to AP Mode will you be able to use Python to do swarm programming. The script set-ap-mode.py will help you set the Tello Edu to AP Mode. To reset the Tello Edu back to Station Mode, turn on the drone and then hold the power button for 5 seconds. Below is an example usage of the script; you will need to provide the SSID and password of the router to the program. Additionally, make sure your router supports the 2.4 GHz bandwidth, as the drone will not connect to the 5.0 GHz bandwidth.

    python set-ap-mode.py -s [SSID] -p [PASSWORD]

