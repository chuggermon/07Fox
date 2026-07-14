# 07Fox

![07Fox with Retrobar and Stardock WindowBlinds eXperience11 skin applied](https://github.com/chuggermon/07Fox/blob/main/07Fox-example.png)
<p align="center"> <i>07Fox with Retrobar and Stardock WindowBlinds eXperience11 skin applied</i></p>

## About

07Fox was a custom theme for Mozilla Firefox made by [WinClassic user travis](https://winclassic.net/thread/1524/07fox-internet-explorer-mozilla-firefox) that made Firefox resemble Internet Explorer 7.

This repository serves as a fork of this CSS theme so that it remains compatible with the latest Firefox versions (152.0.5 at the time of writing).

## Disclaimer

Almost all work was done by travis, with edits being made only to fix parts of the UI that broke with updates to Firefox. This theme is not entirely accurate as many compromises had to be made in order to maintain functionality.

## Instructions (copied from travis's documents)

Go to about:config and search for 

"toolkit.legacyUserProfileCustomizations.stylesheets" 

and set it to "true", then search for

"svg.context-properties.content.enabled"

and set it to true, then search for

"ui.prefersReducedMotion"

and set the value as "1" (you may need to create it, before you do it select number", then restart Firefox.

Copy the files inside /ffroot to C:\Program Files\Mozilla Firefox (or wherever your Firefox installation is)

Then copy the "chrome" folder inside /profile to %appdata%\Mozilla\Firefox\Profiles\<your profile>

If you don't know which profile you're using since there is many, go to about:support on Firefox and look for the column that says "Profile Folder".
Press the "Open Folder" button next to it and it should open the directory to the profile you're currently using. And you can copy the files inside /profile to it.

## New Additions

I added an experimental dark mode modeled after Windows Media Player 11. To use it, follow the instructions below but use the chrome folder inside 'profile - Dark'.

![07Fox Dark Mode with Retrobar and Stardock WindowBlinds eXperience11 skin applied](https://github.com/chuggermon/07Fox/blob/main/07Fox-dark-example.png)
<p align="center"> <i>07Fox Dark Mode with Retrobar and Stardock WindowBlinds eXperience11 skin applied.</i></p>
<p align="center"> <i>Windows Media Player with WMP 11 skin for comparison.</i></p>
