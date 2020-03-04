# Install Raspiberry Py

* https://downloads.ubiquityrobotics.com/pi.html

On other operating systems we recommend using [etcher](https://etcher.io/) to flash images onto SD cards.

Getting Started
NOTE: When the Raspberry Pi boots for the first time, it resizes the file system to fill the SD card, this can make the first boot take some time.

On a Pi3, our image comes up as a Wifi access point. The SSID is ubiquityrobotXXXX where XXXX is part of the MAC address. The wifi password is robotseverywhere.

Once connected, it is possible to log into the Pi with ssh ubuntu@10.42.0.1 with a password of ubuntu. If you connect up a keyboard and mouse enter the password ubuntu at the prompt.

If you are not running on one of our robots run sudo systemctl disable magni-base to ensure that our startup scripts get disabled.


```bash
$ sh ubuntu@10.42.0.1
```

When it was connected

```bash
$ pifi list seen
$ pifi add <ssid> [<password>]
```

```bash
$ sudo locale-gen pt_BR pt_BR.UTF-8
$ sudo dpkg-reconfigure locales
```
```bash
$ sudo apt-get install tightvncserver
$ tightvncserver
$ vncserver :1 -geometry 1024x600 -depth 16 -pixelformat rgb565
```


# Install Jetson Nano


# Example Autonomuous Car
```bash
$ source ~/catvehicle_ws/devel/setup.bash
$ roslaunch catvehicle catvehicle_canyonview.launch
$ gzclient
```
