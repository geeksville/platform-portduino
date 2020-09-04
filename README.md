# Portduino development platform for [PlatformIO](http://platformio.org)

NOTE: YOU DO NOT WANT THIS YET!  Still a WIP.

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

## Development version

```ini
[env:development]
platform = https://github.com/geeksville/platform-portduino.git
board = ...
...
```

# Configuration

Please navigate to [documentation](http://docs.platformio.org/page/platforms/linux_x86_64.html).

# TODO

* change to be just a platform.json file and reference the standard linux-64/linux-arm platforms to provide the implementation.
* possibly just send in PRs for the standard linux projects and add let 'portduino' be a framework for them