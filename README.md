# widevine-for-postmarketOS
Get Widevine and install DRM on PostmarketOS (Alpine ARM64).
This is based upon the [widevine-aarch64](https://aur.archlinux.org/packages/widevine-aarch64) package from Arch's AUR.

# How to install

    sudo apk add git
    git clone https://github.com/mtb0x1/widevine-for-postmarketos
    cd widevine-for-postmarketos
    sudo ./install

Then based on whether you use Chromium or Firefox, as a user:

    register_widevine_chromium # Chromium

OR:

    register_widevine_firefox # Firefox
