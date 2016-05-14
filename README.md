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
4. Open a Crosh window and type `shell`
4. Run `sudo sh ~/Downloads/crouton -t xfce`
5. Wait until the operating system installs (15-20 minutes)
6. Launch the new operating system `sudo enter-chroot startxfce4`
7. Install git -> `sudo apt-get install git`
8. `git clone https://github.com/dsrikant/BufferOverflow.git`


## Helpful and Useful Links

### Buffer Overflows
- http://phrack.org/issues/49/14.html
- https://www.defcon.org/images/defcon-15/dc15-presentations/Moyer/dc-15-moyer-WP.pdf


### Heap Spraying
- https://www.blackhat.com/presentations/bh-europe-07/Sotirov/Presentation/bh-eu-07-sotirov-apr19.pdf


### Networks
- https://github.com/openssl/openssl
- https://technet.microsoft.com/en-us/library/cc775637(v=ws.10).aspx
