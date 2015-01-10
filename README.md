# Video.js VLC

Video.js VLC Tech plug-in

A Video.js tech plugin that add VLC fallback.

## Getting Started

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

Supported content type will depends on your VLC installation, but potentially it should support the following list:
 * video/mp4(.mp4)
 * video/mp4(.m4v)
 * video/ogg(.ogv)
 * video/webm(.webm)
 * video/ogg(.ogg)
 * video/ogg(.anx)
 * audio/ogg(.ogg)
 * audio/ogg(.oga)
 * audio/mp3(.mp3)
 * audio/mpeg(.mp3)
 * application/mpegURL(.m3u8)
 * application/mpegURL(.m3u)
 * application/vnd.apple.mpegURL(.m3u8)
 * application/vnd.apple.mpegURL(.m3u)
 * application/x-mpegURL(.m3u8)
 * application/x-mpegURL(.m3u)
 * application/mpegURL(.m3u8)
 * application/mpegURL(.m3u)
 * application/vnd.apple.mpegURL(.m3u8)
 * application/vnd.apple.mpegURL(.m3u)
 * application/x-mpegURL(.m3u8)
 * application/x-mpegURL(.m3u)
 * audio/mpegURL(.m3u8)
 * audio/mpegURL(.m3u)
 * text/json(.json)
 * text/jsonp(.jsonp)
 * text/xml(.xml)
 * application/json(.json)
 * application/jsonp(.jsonp)
 * application/xml(.xml)
 * image/jpeg(.jpg)
 * image/gif(.gif)
 * image/png(.png)
 * text/html(.html)
 * video/flv(.flv)
 * video/mp4(.mp4)
 * video/mp4(.f4v)
 * video/quicktime(.mov)
 * video/mp4(.m4v)
 * application/f4m+xml(.f4m)
 * application/mpegURL(.m3u8)
 * application/x-mpegURL(.m3u8)
 * application/vnd.apple.mpegurl(.m3u8)
 * application/vnd.ms-ss(.manifest)
 * video/flv(.flv)
 * video/mp4(.mp4)
 * video/mp4(.f4v)
 * video/quicktime(.mov)
 * video/mp4(.m4v)
 * application/f4m+xml(.f4m)
 * audio/mp3(.mp3)
 * audio/mp4(.m4a)
 * audio/mpeg(.m4a)
 
 As this cannot be determined in advance, this plug-in always return success on file type support test. It's why you should always put it at the end of techOrder property.

## Release History

 - 0.1.0: Initial release
