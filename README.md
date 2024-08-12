# Firefox Paradise Theme
*Last updated August 2024 - Supports Firefox 128+*

![startpage](https://github.com/nathandaven/startpage/blob/master/preview.gif?raw=true)


My custom Firefox userChrome profile, setup with right handed vertical tabs, compact layout, and MacOS/Paradise colors theming.

See [nathandaven/startpage](https://github.com/nathandaven/startpage) for my accompanying start page extension.

This is designed custom fit for me, so don't expect much configurability. See [here](https://github.com/ranmaru22/firefox-vertical-tabs) for the more standard theme this is based on.


## Installation
0. go to about:config in your URL bar, search for toolkit.legacyUserProfileCustomizations.stylesheets and set it to true
1. locate the firefox profile folder by going to the *hamburger menu* > *help* > *more torubleshooting information*
2. click *show in finder* or *open folder* next to profile folder
3. open the highlighted folder (should look something like "13s123f4.default-release")
4. create a folder named "chrome" if it doesn't exist already
5. paste files from repo into this folder, or `git clone https://github.com/nathandaven/firefox-paradise-theme.git` and restart firefox (command-q/alt-f4 and reopen)
6. install Tab Center Reborn
7. open the extension settings, enable compact mode, and copy the contents of `tab-center-reborn.css` into the stylesheet section
8. profit


## Older Versions

Decided to manage these files in a github repo for better maintainability. See here for the original gists:

- My custom Firefox userChrome.css based on this [project](https://github.com/ranmaru22/firefox-vertical-tabs):  
https://gist.github.com/nathandaven/67f293758f13971882adf334b66db8ed

- My Tab Centern Reborn custom css config: 
https://gist.github.com/nathandaven/93f52bdc881a6e7cc621e097404b0d01


## Screenshots

#### MacOS

![startpage](https://github.com/nathandaven/startpage/blob/master/dark-screenshot.png?raw=true)

![startpage](https://github.com/nathandaven/startpage/blob/master/light-screenshot.png?raw=true)

#### Windows

![dark windows](https://github.com/user-attachments/assets/594da29e-aadf-4c93-a9ba-193ad40a9562)

![light windows](https://github.com/user-attachments/assets/3fe97cc5-51cd-4cbe-a32f-1d7d55c5f297)
