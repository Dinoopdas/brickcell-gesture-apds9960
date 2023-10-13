
> Open this page at [https://gbantique.github.io/brickcell-gesture-apds9960/](https://gbantique.github.io/brickcell-gesture-apds9960/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/gbantique/brickcell-gesture-apds9960** and import

## Edit this project

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/gbantique/brickcell-gesture-apds9960** and click import

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>

## Credits to the original author for sharing their work for us. Thank you
1. [https://github.com/limaodong118/pxt-zjwl-apds9960/](https://github.com/limaodong118/pxt-zjwl-apds9960/)
Changelog:
* Changed namespace from "ZjwlGesture9960" to "Brickcell".
* Removed class "APDS9960", variables and methods exposed to root namespace.
* Added subcategory "gesture apds9960" to appear under the "Brickcell" block.
* Modified onGesture() method to work properly for Brickcell requirements.
* Removed the forward and backward gesture (microbit keeps restarting or hangs).