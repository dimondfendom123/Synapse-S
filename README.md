# Synapse-Sirhurt
Synapse S is the project name for the Synapse Blue and (soon) Synapse Legacy custom UI's for SirHurt


## How to setup

1.  Install prerequisites (.net framework)
2. Install Synapse Installer.exe from the latest release
3. Once its finished, launch Synapse Blue and you're good to use the UI.

(Note: if you want to **uninstall** Synapse Blue, go to settings, press "Open Synapse Folder", close Synapse Bue, and delete the entire folder. This will be simplified in the near feature)

The Synapse Installer should make a shortcut named "Synapse" on the start menu, so whenever you want to open it up again, you can search for it in the windows search bar
 
I temporarily disabled the experimental panel because it was just way to buggy and not worth the time to fix, but I will fix it soon. 
# Synapse Blue Showcase
[![Synapse Blue Preview](https://img.youtube.com/vi/wVV36wQ0nF4/0.jpg)](https://youtu.be/wVV36wQ0nF4)
<img src="https://i.imgur.com/ZsFzoIM.png">
<img src="https://i.imgur.com/mU50s8G.png">

# Documentation 

First off, we would like to give a huge thanks to @kalash789 and his team for sponsoring this UI. Without him, none of this would be possible.

A couple months back, postrict made this very identical copy of Synapse Blue, but never released it due to various bugs and it being attached to an API that was very unstable. Kalash789 encouraged us heavily to continue developing this UI, so we decompiled an old build (because postrict lost the project) and got to work.

Animations 

Postrict managed to replicate almost every animation that Synapse Blue featured, most notably the boostrapper transition, sidebar hoover effects, grid transition animations and various others. Some animations were slightly improvised, such as the script items hover/click and notification intros.

Injection

We managed to hide the sirhurt.exe or injection prompt by developing a custom injector that sirhurt.exe runs within. This can be turned off if you like, but injection indication is already validated through the injection grid process, each step of that injection process was rightfully programmed to validate the step. If you encounter any problems with injection, you can turn off indication logic in the experimental panel.'

Known Issues

Synapse Blue did take alot of effort to develop, but nothings perfect, and it does come with a little bugs. Most effectively, when you close Synapse Blue, the application seems to crash and take a few seconds to actually close. This will be fixed in the near feature.  

Console

Vapelate managed to implement Roblox console logs with C# and LuaU communications, therefore a lua script has been placed in your auto-execute folder to display the logs inside the console. Though the optimization isn't the best, when the console logs get too large, the injection process and the whole program in general starts to misbehave, so i've made the program clear the console logs once it hits 6.5kb to avoid this. However, I assure you a better optimization solution will be added in future updates.

We hope you enjoy this software as much as it was to create it, and again thank you kalash789 for sponsering this UI

# To-Do

 - Synapse Legacy
 - Experimental Options support
 - Better UI Resizing optimization
 - Clear Conformation
 - More Options

Note: This software does not give out SirHurt for free, you will have to buy SirHurt on your own at https://sirhurt.net or at all resellers available. Window defender might flag SirHurt as a false positive, meaning you will have to add the local folder as an exclusion. We will not leak your SirHurt data anywhere, our product is safe and made by a former staff with good relations working for SirHurt.

