# Debian_Version_upgrade

The short version, assuming you haven’t added third-party repositories:

* ensure your Debian 11 system is fully updated (sudo apt update && sudo apt upgrade)
* replace bullseye with bookworm in /etc/apt/sources.list
* add non-free-firmware if necessary
* update your repository caches (sudo apt update)
* run a minimal upgrade (sudo apt upgrade --without-new-pkgs)
* run a full upgrade (sudo apt full-upgrade)
