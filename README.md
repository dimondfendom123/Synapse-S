# Synapse-S
First off, we would like to give a huge thanks to @kalash789 and his team for sponsoring this UI. Without him, none of this would be possible.

A couple months back, postrict made this very identical copy of Synapse Blue, but never released it due to various bugs and it being attached to an API that was very unstable. Kalash789 encouraged us heavily to continue developing this UI, so we decompiled an old build (because postrict lost the project) and got to work.

Animations 

Postrict managed to replicate almost every animation that Synapse Blue featured, most notably the boostrapper transition, sidebar hoover effects, grid transition animations and various others. Some animations were slightly improvised, such as the script items hover/click and notification intros.

Injection

We managed to hide the sirhurt.exe or injection prompt by developing a custom injector that sirhurt.exe runs within. This can be turned off if you like, but injection indication is already validated through the injection grid process, each step of that injection process was rightfully programmed to validate the step. If you encounter any problems with injection, you can turn off indication logic in the experimental panel.

Console

Vapelate managed to implement Roblox console logs with C# and LuaU communications, therefore a lua script has been placed in your auto-execute folder to display the logs inside the console. Though the optimization isn't the best, when the console logs get too large, the injection process and the whole program in general starts to misbehave, so i've made the program clear the console logs once it hits 6.5kb to avoid this. However, I assure you a better optimization solution will be added in future updates.

We hope you enjoy this software as much as it was to create it, and again thank you kalash789 for sponsering this UI

Note: This software does not give out SirHurt for free, you will have to buy SirHurt on your own at https://sirhurt.net or at all resellers available. Window defender might flag SirHurt as a false positive, meaning you will have to add the local folder as an exclusion. We will not leak your SirHurt data anywhere, our product is safe and made by a former staff with good relations working for SirHurt.
