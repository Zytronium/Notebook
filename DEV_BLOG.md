# Dev Blog
My blog for the process of developing this app.

## Day 1
My first step after creating the base React Native template project with Expo is to ensure it works on my phone. I ran
`npx expo start`, made sure my phone and computer were on the same network, and scanned the QR code using the Expo Go 
app on my phone. It failed to connect. Already ran into a wall and I haven't even started yet. How fun...

After a little while of debugging, I gave in to my natural impulses and asked AI. It thought I was running WSL on Windows
at first until I corrected it. I am running Linux, not a VM and not WSL. Anyway, it confirmed my suspicion that the issue
was my firewall (I've had firewall issues on this laptop many times since I got it...), but now it's telling me that I 
need to update Expo Go on my phone to open the project. No big deal; I updated it and tried again. Still telling me I 
need a newer version (that doesn't exist yet). I'm almost ready to give up and I haven't even started yet

After another chat with AI, I finally got passed it. Now I'm getting yet ANOTHER error when it finished building. In
fact, FOUR errors. I want to scream. I just want to test the base template that's supposed to work out of the box.
In the middle of debugging these errors, my computer tells me it's on low battery. But it's charging. What? I repluged
the charger and tried a different charger (luckily, it uses USB C to charge so I have spares), but it still won't charge.
I might have to take my computer to the shop before I can get this stupid React Native template to run on my phone.

Oh well, time to commit this monstrosity before I lose what little work I've done so far.