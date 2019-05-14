# good_info
a collection of good stuff over time

Keep SSH Session Alive (place code in ~/.ssh/config)

Host *\
ServerAliveInterval 120\


# switching gcc compiler versions

gcc –v or g++ -v # will tell you the currently active gcc version
module avail gcc# This will show you the list of all available modules module load gcc-6.3.0 # loads indicated gcc version (must be in avail list) module unload gcc-6.3.0 # reverts back to default one
# If you want to load a different version - first unload otherwise they stack



Ionic Tips

after initial installation:


npm uninstall ws
npm install @ionic/app-scripts@latest
