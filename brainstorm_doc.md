Download the latest Debian image from beagleboard.org/latest-images. Install SD card programming utility Download and install balenaEtcher. Boot your board off of the SD card Insert SD card into your (powered-down) board, hold down the USER/BOOT button (if using Black) and apply power, either by the USB cable or 5V adapter. Enable a network connection https://elinux.org/Beagleboard:BeagleBoneBlack_Debian#Flashing_eMMC

Errors installing opkg -Generating configuration files for opkg, please wait.... -No option for 'aclocal' given. Possibly you have forgotten to use 'ACLOCAL_FLAGS='? -aclocal --install -I m4

(WORKING) opencv installation https://stackoverflow.com/questions/15320267/package-opencv-was-not-found-in-the-pkg-config-search-path https://github.com/jayrambhia/Install-OpenCV/tree/master/Ubuntu clone https://github.com/jayrambhia/Install-OpenCV.git then run: chmod +x opencv_latest.sh and ./opencv_latest.sh

opkg https://stackoverflow.com/questions/30569261/installing-opkg error: libarchive not found https://unix.stackexchange.com/questions/252130/configure-error-libarchive-not-found error: No package 'libcurl' found https://stackoverflow.com/questions/42115972/configuration-failed-because-libcurl-was-not-found

debian 10 gui https://forum.beagleboard.org/t/debian-10-x-buster-monthly-snapshots/31203 (images) (download lxqt) accessing gui: https://subscription.packtpub.com/book/hardware_and_creative/9781788293136/1/01lvl1sec11/accessing-the-beaglebone-blue-remotely-via-wlan https://www.linuxquestions.org/questions/debian-26/gtk-warning-%2A%2A-cannot-open-display-0-0-a-807450/ (cant open display solution) camera/opencv instructions (disregard, opencv installation above works) http://derekmolloy.ie/beaglebone-images-video-and-opencv/ opencv installation - https://linuxize.com/post/how-to-install-opencv-on-debian-10/ cmake installation - https://linuxhint.com/install-cmake-on-debian-10/

running capture.c error: libv4l2 not found https://superuser.com/questions/1022116/ffmpeg-build-with-v4l2 converting .raw to mp4 error: ffmpeg not found https://superuser.com/questions/1022116/ffmpeg-build-with-v4l2

camera live feed (Option 1) install guvcview https://ubuntuhandbook.org/index.php/2018/10/guvcview-2-0-6-released-install-ubuntu/ install fswebcam https://installati.one/debian/10/fswebcam/ run command: guvcview (Option 2) mjpg_streamer tutorial: https://www.youtube.com/watch?v=p5upoyRPNIg

Beaglebone as Flight unit https://beaglebluevoyager.com/configuring-beagle-bone-blue-as-flight-controller-unit/