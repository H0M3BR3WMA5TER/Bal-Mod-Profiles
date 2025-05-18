# Bal-Mod-Profiles
A WIP batch script that allows someone to swap between different mod folders for Balatro, in essence making a different 'Mod Profile'

Have you ever had mods you've wanted to use, but just don't seem keen on working together and playing nice?
I did. And I had times where I kinda wished that I could declutter some of my mods without losing them. Just, setting them to the side.

Now, This allows for that. 

With the use of multiple mod folders and, what I call, a 3-point-turn for folders, I managed to rotate from one mod folder to the other. Then, I started building ontop of that.
Building a kinda primative CLI (I know its not an actual CLI but it has no GUI of its own until I learn C), adding in listing of installed mods in the folders.
Just all neat little additions.

Things I need to do:
- Find a suitable global variable to use with ModSwap.cmd
- Change ModSwap.cmd to ModSwap.bat because its annoying me that both aren't the same extension
- Find a way to use more than 2 mod profiles
- Impliment a metadata system to add unique naming to mod profiles
- Find a way to hook it into Balatro on Steam launch without making the script into an exe named Balatro.exe and putting it in the steam folder and renaming the original Balatro.exe
