# b-sty

flink.pug
- .\themes\mytheme\layout\flink.pug

third-party.styl
- .\themes\mytheme\source\css\_layout\third-party.styl


from

``````
.has-jax
  overflow: auto
``````

to

``````
.has-jax 
  overflow: visible
``````

var.styl
- .\themes\mytheme\source\css\

``````
// font
$fontEnable = hexo-config('font') && hexo-config('font.enable')
$font-family = $fontEnable ? convert(hexo-config('font.font-family')) : Lato, Helvetica Neue For Number, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, PingFang SC, Hiragino Sans GB, "Microsoft YaHei", Helvetica Neue, Helvetica, Arial, sans-serif,zgFont
$code-font = $fontEnable ? convert(hexo-config('font.code-font')) : consolas, Menlo, "PingFang SC", "Microsoft YaHei", monospace, Helvetica Neue For Number,zgFont
$site-name-font = convert(hexo-config('blog_title_font.font-family')) || '"Titillium Web",Lato,PingFang SC, Hiragino Sans GB, "Microsoft JhengHei", "Microsoft YaHei", Helvetica Neue, Helvetica, Arial, sans-serif'
``````
