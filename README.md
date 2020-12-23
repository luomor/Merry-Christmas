#圣诞节电子贺卡——用代码来泡妹子

用空闲时间设计了一张圣诞节的电子贺卡，用CSS3实现动画效果

使用github的pages或者coding的项目演示来部署代码，将项目地址生成一个二维码

###使用场景

*直接把二维码直接发给妹子

*把二维码打印在送给妹子的礼物包装盒上

*发挥你的创造力通过各种途径让妹子看到它

这是我为给妹子部署的：

<img src="qrcode.png" width="200">

设计稿PSD下载地址：<a href="http://pan.baidu.com/s/1gdw3lEr" target="_blank">[下载]</a>

cnpm install
grunt build

grunt build --force

```
grunt build --force        
Loading "imagemin.js" tasks...ERROR
>> ReferenceError: primordials is not defined
Warning: Task "imagemin" not found. Used --force, continuing.

Done, but with warnings.

grunt --version
grunt-cli v1.2.0
grunt v0.4.5

cnpm install -g grunt

grunt --version      
grunt-cli v1.3.2
grunt v0.4.5

cnpm install -g gulp

/usr/local/bin/gulp
```

```
imagemin ReferenceError: primordials is not defined
```

```
grunt build -v

cnpm install grunt-real-favicon


deprecate grunt@0.4.5 › minimatch@~0.2.12 Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
deprecate grunt@0.4.5 › coffee-script@~1.3.3 CoffeeScript on NPM has moved to "coffeescript" (no hyphen)
deprecate grunt@0.4.5 › glob@3.1.21 › graceful-fs@~1.2.0 please upgrade to graceful-fs 4 for compatibility with current and future versions of Node.js
deprecate grunt@0.4.5 › findup-sync@0.1.3 › glob@3.2.11 › minimatch@0.3 Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
deprecate grunt-contrib-imagemin@0.9.4 › imagemin@3.2.2 › vinyl-fs@1.0.0 › glob-stream@4.1.1 › minimatch@^2.0.1 Please update to minimatch 3.0.2 or higher to avoid a RegExp DoS issue
deprecate grunt-contrib-imagemin@0.9.4 › imagemin@3.2.2 › vinyl-fs@1.0.0 › graceful-fs@3.0.12 › natives@^1.1.3 This module relies on Node.js's internals and will break at some point. Do not use it, and update to graceful-fs@4.x.
deprecate grunt-contrib-imagemin@0.9.4 › imagemin@3.2.2 › imagemin-gifsicle@4.2.0 › gifsicle@3.0.4 › bin-wrapper@3.0.2 › download@4.4.3 › gulp-decompress@1.2.0 › gulp-util@^3.0.1 gulp-util is deprecated - replace it, following the guidelines at https://medium.com/gulpjs/gulp-util-ca3b1f9f9ac5
```

```
"grunt": "~0.4.2",
"grunt-contrib-uglify": "^0.6.0",
"grunt-contrib-clean": "^0.6.0",
"grunt-contrib-cssmin": "^0.10.0",
"grunt-contrib-imagemin": "^0.9.2"

cnpm install --save-dev grunt
cnpm install --save-dev grunt-contrib-uglify
cnpm install --save-dev grunt-contrib-clean
cnpm install --save-dev grunt-contrib-cssmin
cnpm install --save-dev grunt-contrib-imagemin
```