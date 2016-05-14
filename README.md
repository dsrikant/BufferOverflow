# BufferOverflow

## Enable Developer Mode on Your Chromebook

1. Hold Esc and Refresh keys and tap Power Button

2. The Recovery screen will say “Chrome OS is missing or damaged.”

  a. Press Ctrl-D

3. The next screen will say “To turn OS Verification OFF< press ENTER.”

  a. Press ENTER

4. Finally you'll see a screen that says “OS verification is OFF”

  b. Don't press space


## Download Crouton

1. Search for secure shell in the Chrome Store and add plugin
2. Search for crosh in the Chrome Store and add plugin
3. Download crouton from this link -> https://goo.gl/fd3zc
4. Run `sudo sh ~/Downloads/crouton -t xfce`
5. Wait until the operating system installs (15-20 minutes)
6. Launch the new operating system `sudo enter-chroot startxfce4`
7. Install git -> `sudo apt-get install git`
