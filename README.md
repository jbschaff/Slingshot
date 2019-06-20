# Slingshot

Slingshot solves one problem — getting a URL *from* macOS Chrome/Safari *to* a contact in iMesssage with as few taps, apps, and services as possible. Happy Slinging!


## Installation

### Create a service using Automator:

1) Download [Slingshot.zip](https://www.dropbox.com/s/yoakzl0cd45aswp/Slingshot.zip?dl=1), and then unzip.

2) Right click open Slingshot.workflow, and select ‘Open With’ Automator.

2) Add your phone number following `“+1` in lines 13 and 28 (assuming country code is USA).

`set targetBuddy to "+12148881234”`

3) Save & Close Automator. Open Slingshot.workflow file and select install to add as a service.


### Create your keyboard shortcut:

3) Go to System Preferences > Keyboard > Shortcuts > Services in Sidebar

4) Scroll to the section General > Slingshot — make sure the box is selected & add your desired keyboard shortcut


### Tips:

The browser window containing the intended URL to send *must* be the frontmost app — i.e. not greyed out, minimized, or behind any other windows.

Check your browser keyboard shortcuts to avoid conflicts with global shortcuts!
