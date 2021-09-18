# sublime中安装的插件

ABAP

ConvertToUTF8

HTML-CSS-JS Prettify

Insert Nums

Language SAP

Tabnine

Package Control



sublime中对abap进行高亮

第一步：访问https://github.com/PavelJaros/ABAP-Sublime-Plugin，下载ABAP-Sublime-Plugin.7z

第二步：将其解压到Preferences -> Browse Packages下，并添加package-metadata.json

```json
{"url": "http://www.jaros.in/item/abap-syntax-highlighting-for-sublime-text", "version": "2013.05.21.01.20.00", "description": "ABAP syntax highlighter and snippets"}
```

第三步：通过ctrl+shift+p，选择abap后使用

参考：https://stackoverflow.com/questions/19096626/sublime-text-3-abap-syntax-highlighting-color-scheme



package control无法安装或下载太慢：https://github.com/wilon/wilon.github.io/issues/8