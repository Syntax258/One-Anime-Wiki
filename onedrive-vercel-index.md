# onedrive网盘目录搭建

参考一个非常酷炫且不需要服务器的网盘目录：https://github.com/spencerwooo/onedrive-vercel-index

使用过OneIndex类似的同学应该很熟悉，参照Github相关教程搭建即可，也可以选择自己熟悉的类似项目。onedrive-vercel-index支持vtt字幕，但是播放器默认字体可能较小，可以在globals.css中自行定义字幕大小。

```
# globals.css
.plyr__captions {
  --plyr-font-size-small: 20px;
  --plyr-font-size-base: 24px;
  --plyr-font-size-large: 28px;
  --plyr-font-size-xlarge: 36px;
}
```

演示站点：https://oneanime.eu.org/

针对字幕格式转换和时移的小工具：
1. [Subtitle Converter | Free tool | GoTranscript](https://gotranscript.com/subtitle-converter)
2. [Sync subtitles online: easy timing adjuster | Subtitle Tools](https://subtitletools.com/subtitle-sync-shifter)
