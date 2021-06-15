# ff-themes
Various themes to customize my Firefox.  

# Building
```bash
cd <theme>
web-ext build
```  

# Installing
Follow the steps [here][1] to self-distribute your theme. Once uploaded,
you can install it for your browser.  

# Notes
It is possible a theme does not work well with your browser's background
color. That background color cannot be altered by an extension or theme.
To change it, modify the `browser.display.background_color` property 
in the `about:config`.


[1]: https://extensionworkshop.com/documentation/publish/submitting-an-add-on/
[2]: https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/theme
[3]: https://github.com/mozilla/web-ext
