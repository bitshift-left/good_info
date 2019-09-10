# good_info
a collection of good stuff over time

Keep SSH Session Alive (place code in ~/.ssh/config)

Host *\
ServerAliveInterval 120\


# switching gcc compiler versions

gcc –v or g++ -v # will tell you the currently active gcc version
module avail gcc# This will show you the list of all available modules module load gcc-6.3.0 # loads indicated gcc version (must be in avail list) module unload gcc-6.3.0 # reverts back to default one
# If you want to load a different version - first unload otherwise they stack


##Notes

Add `export` statements to `/etc/profile` for system wide application
Otherwise, `~/.profile`
i.e. `export PATH=$PATH:/usr/local/go/bin`

tar -C <output parent directory> -xcf <file> 


Ionic Tips

after initial installation:


npm uninstall ws
npm install @ionic/app-scripts@latest


Loading an Image onto SD Card (for Raspberry Pi)

xz -d "image_of_os.img.xz"   // unpack image
diskutil list
diskutil unmountDisk /dev/disk<id>
sudo dd if=<image path> of=/dev/disk<id> bs=1

