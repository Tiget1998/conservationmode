# conservationmode
Terminal command that can trigger Lenovo's built in conservation mode from Linux

Conservation mode is a function for most modern Lenovo laptops. When plugged in the laptop will not charge if above ~60% battery.
Ideal if you are planning to use it somewhere, where it is plugged in all the time as to not damage the battery.
Normally it would require you to switch to Windows in order to trigger this function. Or run a string of commands in the terminal to trigger it.
This is a useful shortcut of those commands.

# install
------ no terminal command --------
1. Go to any directory you want the file to be installed in.
2. Run `git clone https://github.com/Tiget1998/conservationmode.git`
3. Done. Use it by running `sudo bash conservationmode <on/off>`.
You need to be in the install directory for this to work everytime you want it to toggle it.

------ With terminal command ------
1. Go to any directory you want the file to be installed in.
2. Run `git clone https://github.com/Tiget1998/conservationmode.git`
3. `cd <directory it was cloned into>`
4. `sudo cp conservationmode /usr/local/bin`
5. You can use any editor you like here, here gedit is picked. `sudo gedit ~/.bashrc`
6. Go to the bottom of the file and paste `export PATH=$PATH:~/usr/local/bin`
7. Reboot
8. Run by opening a terminal and typing `sudo conservationmode <on/off>`.
This can be toggled from any directory.
