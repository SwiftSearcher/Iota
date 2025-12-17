IOTA

Internet Obliterates Tracking Application

Iota is a bug with the CK-Authenticator extension, causing it to just... not turn on? This isn't really an exploit per se, rather a fatal flaw in CK-Auth. I still can't figure out why it happens, but I might as well go ahead and tell you how to make it happen.

The "exploit"

When your browser opens, CK has a "startup phase". It prevents internet access untill it turns on so it can filter. On managed WiFi, this startup phase is always successful. On non-managed WiFi? Uhh... not really. For some reason, it.. just doesn't? It doesn't disable WiFI. And it takes at least 5 minutes to turn back on. Sometimes never. All you need to do is crash or reset your computer a bunch of times. If you have debug you can use Ctrl+Alt+Shift+K. If flags are disabled just use Pwr+Shift+Reset. Just open up your browser after each reset. Check if the extension is off. If it is off and websites still load, congrats! Please note that this doesn't work on school WiFi (like I said earlier). Also for you freaks, your browser history can still be seen. Get your mind out of the gutter.

-Swift
