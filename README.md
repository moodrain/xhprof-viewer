### Moodrain Xhprof Viewer

 [Online Version](https://s1.moodrain.cn/xhprof.html)

#### Usage

1. Install xhprof extension from [tideways/php-xhprof-extension](https://github.com/tideways/php-xhprof-extension)
2. Get xhprof json file

```
<?php

tideways_xhprof_enable(TIDEWAYS_XHPROF_FLAGS_MEMORY | TIDEWAYS_XHPROF_FLAGS_CPU);

my_application();

file_put_contents('path/to/xphrof.json', json_encode(tideways_xhprof_disable()));
```
3. Visit [Online Version](https://s1.moodrain.cn/xhprof.html) and select the xhprof.json

#### ScreenShots

![ScreenShot 1](/screenshot/1.png)
![ScreenShot 2](/screenshot/2.png)