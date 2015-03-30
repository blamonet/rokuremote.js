# rokuremote.js
Roku Remote in JavaScript

![Screenshot 1](https://raw.githubusercontent.com/blamonet/rokuremote.js/master/screenshots/remote.png)

![Screenshot 2](https://raw.githubusercontent.com/blamonet/rokuremote.js/master/screenshots/app.png)

# Usage

In roku_remote.html update roku_ip_address to your Roku's IP address. Then just open the file in your browser.
This has been tested in Chrome and Safari. 

The apps option only works natively with Safari. Other more secure browsers, such as Chrome, require you to start it in an alternative mode to get around XSS protections. 

Example of overriding security for Chrome in Mac OS X. I don't really suggest this. Do this at your own risk.
> open -a Google\ Chrome --args --disable-web-security

# Keyboard shortcuts

* Arrow keys for navigation
* Spacebar: Play/Pause
* Enter: Select
* Back: b
* Home: h
