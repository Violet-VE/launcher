>I no longer work on this project, and I'm not likely to working on it anytime soon. If anyone would like to maintain it, please contact me at theduck.dev@gmail.com

Duck Launcher
========

Duck Launcher is an application launcher and a dock made for linux. 
It's supposed to be beautiful while being useful. With the Duck Launcher, all your basic needs are pleased in one place:
  -Launch your apps
-------
  You can access your favorite apps easily on the dock, or you can find all your apps simply by clicking on the top icon.
  -Browse your files
---------
  [Work in progress]
  You will be able to access your files easily, without having to open the file manager each time.
 -Star
--------
  "Star" is kind of an extension of the file browser and the app launcher: you can choose any application, file or folder   and add it. But these can be separated in blocks. Let's say you're a graphic artist, then you'll add a block named       "Graphics" and add a few apps, like blender and gimp, and a folder where you store your files, and perhaps a file your     working on right know.
  -Plugins
---------
   With plugins, the searching experience pushes its limits. Whereas just searching for apps, you could potentially search for anything, be it from a web service or from some local media. You just need a plugin for what you want to search. Due to the flexibility of the plugin system (as it uses web languages for the user interface), a plugin could even be a simple application.  
  -Customize Duck Launcher
-------
  With the duck settings, you can customize a lot of things, like your dock apps, the launcher's color, etc...
 -Screenshots
-------
 Check out http://the-duck.github.io/
 -Install:
-------
  To install, you must have a debian-based system.      
  If you are not on an ubuntu based system     
      -From gihtub, download and extract source, then cd to the launcher-master and run:`debuild -i -us -uc -b`. You'll get a .deb file, and you can install by double clicking on this file...
    
  To install on ubuntu, run:     
    `sudo add-apt-repository ppa:the-duck/launcher`       
    `sudo apt-get update`       
    `sudo apt-get install duck-launcher`
  
