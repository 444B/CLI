# USB+Laptop
This is a guide for advnanced installation
Please note that you can safely make changes to you existing laptop but you should read these resources and also do your own research before proceeding. I take no resposnability and am not liable for any potential damage you cause to your machine or any loss of data. That being said:

Dual booting can be done on Windows, Linux, Mac or your smart toaster (potentially ;) )
# Steps
- You will need a USB that has at least 8Gb of space. Find a USB you will not neet anymore as this process will wipe the contents and format it to a filesystem where you wont be able to store data (until you reformat it, it is not permanent)
- Download a .iso of you favourite distro (Ubuntu 20.04 is reccomended) You should always verify the SHA256 checksum of the downloaded file to check the integrity. [Link](https://security.stackexchange.com/questions/189000/how-to-verify-the-checksum-of-a-downloaded-file-pgp-sha-etc)
- Download [Balena Etcher](https://www.balena.io/etcher/) for your OS
- Follow the steps in Balena to flash the .iso to the correct device (make *sure* you are not flashing to your local hard drive or an external drive. This is the only warning you will get) Read up on any further guides if necessary
- Turn off computer and enter the USB. 
- Enter into the BIOS and change the boot order and place the USB first. Look up guides for you computer manufacturer on how to enter the BIOS. Typically it is by shutting off the computer and restarting while holding F5 o F12 or some other F key
- With the Boot order changed, use the BIOS settings to save and restart the machine using new BIOS settings
- The OS loaded into the USB should launch.


# Install
If everything above was successful, you should be seeing a new OS running on your hardware. Well done!
Now you get to pick a few things
- To load from the USB in a live environment or to install to the hard drive. You can install alongside the existing OS or you can replace it. Pick according to your needs
- A username (remember this)
- A hostname (name of the machine)
- A password (very important)

That should be about everything. Now you have a working Linux distro accoridng to you use case, we can continue with the CLI course
