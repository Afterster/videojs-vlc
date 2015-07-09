# Video.js VLC

Video.js VLC Tech plug-in

A Video.js tech plugin that add VLC Media Player fallback.

## Getting Started

VLC Web Plugin must be installed on the browser to work.

Once you've added the plugin script to your page, you can use it with any supported video:
 * Include JavaScript files
```html
<script src="video.js"></script>
<script src="videojs-vlc.js"></script>
```
 * And add this new tech to the player:
```html
data-setup='{ "techOrder": ["vlc"] }'
```

There's also a [working example](example.html) of the plugin you can check out if you're having trouble.

## Documentation
### Plugin Options

This plugin doesn't have any option.

### Supported content type

Supported content type will depends on your VLC installation, but basically it should support almost all [audio](https://www.videolan.org/vlc/features.php?cat=audio) and [video](https://www.videolan.org/vlc/features.php?cat=video) formats.
 
As this cannot be determined in advance, this plug-in always return success on file type support test. It's why you should always put it at the end of techOrder property.

## Build
Building the plug-in is optional, you can directly use /lib/videojs-vlc.js file but it is good practice to be sure your environment is well configured.
It will also simplify your test as you will be able to use /example.html sample file directly after build.

 * Install npm (node.js)
 * Install grunt: `npm install -g grunt`
 * Install project dependencies: `npm install`
 * Run grunt : `grunt`

## Release History

 - 0.2.0
    - Fix poster image
    - Fix fullscreen
    - Fix autoplay
 - 0.1.0
    - Initial release
