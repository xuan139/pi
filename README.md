# pi installation
# 1.install pi image Imager
# 2.burn pi os to card
# 3.install teamviewer
# 4.enable ssh enable camera enabls ic2 via sudo raspi-config 
# 5.enable teamviewer when sys star 
# 6.fix teamviewer auto launch hdmi problem,fix resolution problem

# install the libusb ,follow the video
https://www.hackster.io/codetricity-oppkey/raspberry-pi-controller-for-ricoh-theta-360-camera-bc4ed9

# fix bug after install lib
https://community.theta360.guide/t/problems-using-ptpcam-on-rpi-with-theta-sc-via-usb/1694

# sudo ldconfig 
fixed that issue.
This was fixed by running: export LD_LIBRARY_PATH=/lib:/usr/lib:/usr/local/lib

