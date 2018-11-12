# Mac Media Key Forwarder [![Build Status](https://travis-ci.org/milgra/highsierramediakeyenabler.svg?branch=master)](https://travis-ci.org/milgra/highsierramediakeyenabler#)

( Formerly known as High Sierra Media Key Enabler )

Mac Media Key Forwarder for [iTunes](https://www.apple.com/itunes/) and [Spotify](http://www.spotify.com).

---

Forwards media keys to iTunes or Spotify directly.

You can prioritize which app you would like to control or you can go with the default behaviour which controls the running app.

The app runs in the menu bar.

Download the compiled application from my [homepage](http://milgra.com/high-sierra-media-key-enabler.html).

If you want even more control over what you want to control you should try [beardedspice](http://beardedspice.github.io).

**Installation**

Apple increased MacOS security with the latest version. Besides allowing MMKF to install in various popups you also have to add it as a trusted app in System Preferences -> Security & Privacy -> Privacy tab -> Accessibility menuitem on the left. You have to click on the lock at the lower left corner then click on the plus icon under app list table and select Mac Media Key Forwarder from Applications folder.  

**Issues you should know about**

The app listens on the event tap for key events. This causes problems in some rare cases, like 
- when changing search engine in Safari's preferences window
- when trying to allow third-party kernel extensions

In these cases simply pause Mac Media Key Enabler from it's menu.

---

Contributors : 
* Michael Dorner ([@michaeldorner](http://github.com/michaeldorner))
* Matt Chaput ([@mchaput](http://github.com/mchaput))
* Ben Kropf ([@ben-kropf](http://github.com/ben-kropf))
* Alejandro Iván ([@alejandroivan](http://github.com/alejandroivan))
* Sungho Lee ([@sh1217sh](http://github.com/sh1217sh))
* Björn Büschke ([@maciboy](http://github.com/maciboy))
* Sergei Solovev ([@e1ectron](http://github.com/e1ectron))

Thank you!!!

---

What's new in version 2.0 :
- app renamed to Mac Media Key Forwarder
- Hungarian localization
- updated icon
- Open At Login state is checked every time the menu is opened so it shows an updated state
- added installation steps to readme because increased MacOS security made it more confusing
- added event-tap related issues to readme because it can cause head scratches in some special cases 

What's new in version 1.9 :
- added open at login menu option
- German localization update
- Korean localization update

What's new in version 1.8 :
- added pause menu option
- added pause automatically menu option : if no music player is running macOS default behavior is used and keys are forwarded to currently active media player
- Russian localization
- German localization
- Spanish localization
- fixed headphone button issue
- added macOS Sierra compatibility if you want explicit music player control there

What's new in version 1.7 :
- fast forward/rewind is possible when iTunes is selected explicitly
- Korean localization
- rumors say that it works with TouchBar

What's new in version 1.6 :
- increased compatibility with external keyboards

What's new in version 1.5 :
- now you can explicitly prioritize iTunes or Spotify
- play button now starts up iTunes or Spotify if they are not running aaaand explicitly selected

What's new in version 1.4 :
- memory leak fixed

What's new in version 1.3 :
- previousTrack replaced with backTrack in case of iTunes for a better experience

What's new in version 1.2 :
- new icon
- source code is super tight now
- developer id signed, its a trusted app now

---
