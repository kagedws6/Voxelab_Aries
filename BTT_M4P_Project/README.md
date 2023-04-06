# Project: AriesKlipper Begins!

I have 2 fully functional Voxelab Aries and one more that was donated to me which will be the first to undergo surgery :) I will keep updating this post as I go.

    Parts list (So Far):

        1x BTT Manta M4p board
        1x BTT CB1 board (if you can find a RPi CM4 this will also work)
        1x BTT CB1 Heatsink
        1x MicroSD card 64GB (for OS install)
        1x SD card 16GB (for Klipper)
        4x TMC2209 drivers
        1x 3d printed mount for the BTT Manta board
        1x Touch display (TBA)

Steps Taken:
    - Removed the bottom cover panel and rear cover panels.

    - Removed stock driver board, LCD/main board, and the USB port board (I plan on reusing at least the USB port board)

    - Using the 3d printed mount for the BTT Manta M4p board, I was looking to see what mods I would need to make to the underside of the Aries. I removed 4 of the tall standoffs and one short (I will include pictures) and then with a high temp glue gun, I fastened the mount to the metal underneath the Aries.**I ended up reusing the Aries Stepper/board fan and its existing mount, and that dictated how I was going to need to position the Manta board**

    - Using the documentation for the BTT Manta and CB1 boards, I downloaded the image file and loaded it onto the MicroSD card. Then placed the MicroSD card and the full-sized SDcard into the manta board before securing it to the 3d printed mount.

    - I connected the power cables from the PSU to the Manta board, connected the board via ethernet to my router, and after a few minutes, I checked my router to get the IP of the device.

    - I accessed the IP on another PC in Google Chrome just to see if its internal web server was up and running.**I actually ran out of time at this point and still need to go back in by connecting over SSH to update everything and make more configuration settings before I start hooking up all the steppers, sensors, etc**