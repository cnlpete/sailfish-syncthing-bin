
[![](https://github.com/cnlpete/sailfish-syncthing-bin/actions/workflows/main.yml/badge.svg)](https://github.com/cnlpete/sailfish-syncthing-bin/actions/workflows/main.yml)

Build it using the virtualmachine:

connect:
> ssh -p 2222 -i ~/SailfishOS/vmshare/ssh/private_keys/engine/mersdk mersdk@localhost

and run the builds:
> mb2 -t SailfishOS-3.3.0.16-armv7hl build
> mb2 -t SailfishOS-3.3.0.16-i486 build


You can check the available targets using:
> sdk-assistant list

Instructions taken from https://sailfishos.org/wiki/Tutorial_-_Building_packages_manually
