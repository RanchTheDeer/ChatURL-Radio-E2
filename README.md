# ChatURL Radio E2

This is a repository holding the latest public release of my ChatURL Radio E2.
E2 stands for Expression 2, which is a programming language for the game Garry's Mod. This is designed for use as an Expression 2 chip.

_*This E2 is meant for advanced users, as the setup is complicated and it's a big buggy! Use with care!*_
 
## Setup

To use the E2, you must first make sure that you have HTTP core enabled (or the server you are playing on has it enabled), and that you/the server has the Streamcore extension ([available here](https://steamcommunity.com/sharedfiles/filedetails/?id=442653157)).
If you're playing singleplayer, you can enable HTTP core using the following command in console:
`wire_expression2_extension_enable http`

After that, visit this site:
http://ytdl.gaerisson-softs.fr/E2/

You should be greeted with this page:
![Login with Steam button page](https://i.ibb.co/cLsGqHt/image.png)

Simply follow the instructions, and when a green "Sign in" button appears on a Steam page, click it.

If all goes well, you'll see a box like this:
![Gaerisson's API Key Page](https://i.ibb.co/VtqrwbZ/image.png)

All you have to do now is hover over your private key to unblur it, then copy it and put it inside the E2 (delete "CHANGEME2" and replace it with "yourkeyhere".
Remember: **keep your key private!** Do **not** share your key or the E2 with the key in it with *anyone*! If they want the E2, direct them to this Github page and tell them to set it up for themselves.

The SteamID provided on the webpage is not required as it'll automatically use the SteamID of the person who spawned it.

To use the (optional but recommended) search function of the E2, you must obtain a Google API key for the Youtube Search v3 API. It's not the easiest of things to do, but the gist of it is as follows:

- Make sure you are signed in with a Google account in your browser, then follow [this](https://console.developers.google.com/apis/library/youtube.googleapis.com) link.
You should see this:
![Youtube Search API Page Screenshot](https://i.ibb.co/PWDJ1MM/image.png)

Click the blue "Enable" button, then wait for it to finish.

You should now see a page like this:
![Youtube Search API Dashboard Screenshot](https://i.ibb.co/SXS6Cgw/image.png)

Click the "Credentials" button at the left, then click the blue "Create Credentials" button at the top, then select "API Key"
![Create Credentials button](https://i.ibb.co/ZGzttZn/image.png)

And you're done! Simply copy the key that it provides you and replace "CHANGEME" in the E2 with your Google API key.
*Note: You are limited to 100 total search requests per day if you're not paying for a Google Cloud subscription, so if the search function suddenly stops working, it's probably you've run out of searches!*

It would probably be wise to save your E2 now that you've done the initial setup, as it won't need to be done again.
In future, I would prefer to store the configuration in a separate E2 file so that you won't have to manually edit newer versions of the E2 if you decide to update. but I'll get round to it eventually.

*Big kudos to Gaerisson for making and maintaining the Youtube converter API that powers this E2! They're the real MVP!
Here's his website (it's mostly in French): http://www.gaerisson-softs.fr/, or click [here](https://translate.google.com/translate?sl=fr&tl=en&u=http://www.gaerisson-softs.fr/) for a translated version*

## Licensing

<html><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.</html>
In Layman's terms, this means that you can use it for whatever you want (provided it's not commercial) as long as you give me fair credit, and as long as you keep it under the same license.
