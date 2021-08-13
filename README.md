# "Edit with Aseprite" - Context-Menu Option
A simple registry snippet, adds an "Edit with Aseprite" option to your right-click menu on Windows. This makes it a bit easier to open GIFs, PNGs, and BMPs with Aseprite on Windows, without having to permanently change the default program for those files.

![Sample Image](sample.gif)

Source URL: https://github.com/JamesO2x/Aseprite-Edit-Context-Menu

## Do take note:
> Selecting multiple files and clicking this option will launch multiple instances of Aseprite.exe! I'm not sure if there is an easy way to send all files to "one window" and open them inside Aseprite as tabs. That would likely require some programming from the develpers to solve, as Windows doesn't support this feature natively.

# How to Install
**Download Method:** To add this option to your context-menu, just save the `asepriteOpenFile.reg` registry file to your computer and double-click to add it to your registry. You can download this file and this readme by clicking the `code` button in the upper right, and selecting `Dowload ZIP` option.

**Copy/Paste Method:** Alternatively, you can just copy the text from the `asepriteOpenFile.reg` above in your browser, then paste the text into a blank Notepad window. Next, save the file as `asepriteOpenFile.reg` and double-click the file to add its data to your registry.

# How to Remove
To remove this option from your context-menu, just open your registry editor and delete this entry.

1. Click the Start button, and type `regedit`
2. An option for Registry Editor should appear. Click it.
3. Navigate in the registry editor to `HKEY_CLASSES_ROOT\*\shell\Open with Aseprite`
4. Right-click on `Open with Aseprite` and delete the whole thing.
5. The option should disappear from your context-menu after this. (you may need to restart your computer for the change to take effect)

# Posible Future Updates?
- Find a way to only show the `Edit with Aseprite` option on certain image files (GIF, PNG, BMP, JPEG, etc) instead of all files. 
- Find a way to send multiple files to one Aseprite window, and open as tabs.
---

If you appreciate this little add-on, feel free to drop me a tip: https://ko-fi.com/jamesorthii

Or check out some of my other work. I make art, animations, and small productivity apps:
- https://jameso2.itch.io/
- https://youtu.be/NSzUt5DZ2tk
- https://jamesorthii.wixsite.com/portfolio
- https://twitter.com/JamesOrthII

![JamesO2](https://i.imgur.com/wlAXu7r.png) JamesO2
