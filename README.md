# PSSX - Python Set Simple Xrandr

PSSX is a simple and easy-to-use tool for setting brightness and Gamma when using Xrandr. It works seamlessly in Xorg environments.

![Python Set Simple Xrandr](https://i.imgur.com/7PxMsde.png)

## How to Use/Install

1.  **if you don't have .xprofile file in /home/user/, you can make it use text editor:**
     ```
     $ cd /home/(your user name)/
     ```
     ```
     $ nano .xprofile
     ```
2. **Just insert: #**
3. **Save it use:**
     ```
      Ctrl + X, press y, and Enter
     ```
5. **Give access to excutable:**
     ```
     $ chmod +x .xprofile
     ```
6.  **Install Python3:**
   - For Debian/Ubuntu:
     ```
     $ sudo apt install python3
     ```
   - For Void Linux:
     ```
     $ sudo xbps-install python3
     ```

3. **Install tkinter module for Python3:**
   - For Debian/Ubuntu and similar distributions:
     ```
     $ sudo apt-get install python3-tk
     ```
   - For Void Linux:
     ```
     $ sudo xbps-install python3-tkinter
     ```

4. **Download PSSX.**
5. **Extract PSSX.**
6. **Open PSSX_v0.0.1**
      ```
     $ cd PSSX_v0.0.1/
      ```
7. **Launch using Terminal .sh file or execute it.**
   ```
   $ ./brightness.sh
   ```
8. **Configure settings according to your preferences, then apply and close.**
9. **Done!**

## Notes

- Make sure to have the necessary dependencies installed before using PSSX.
- You may need to grant execute permissions to the *.sh file before launching it.


