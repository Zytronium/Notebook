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

## Day 2 | Part 1
What a run of bad luck yesterday way! Anyway, I took my laptop to the computer shop and they couldn't fix it. I was 
getting ready to send my laptop in to Lenovo to get it fixed or replaced (it's still under warranty luckily) when I 
decided to ask AI if there's anything I can try first. To my surprise, there was. I simply unplugged the laptop, held 
the power button for a minute, and plugged it back in, and viola, it started charging again! Now that I've fixed my 
laptop, it's time to fix this React Native template. 

When I try `npm install`, I get a ton of errors. Normally, at this point, I'd just quit unless this was for school/work,
but since I'm writing this dev blog, I'll give it one more day. What kind of mobile app developer am I if I can't even
get React Native to work again after successfully using it multiple times in the past?

I found out I can manually install the Expo Go update that's not on Google Play yet, so I did that and then re-installed
SDK 55 for React Native. However, that failed, so I tried again after reinstalling a couple packages, and it STILL 
doesn't work; I got more errors. Time for more AI... The AI told me to install Android Studio because I don't have the
native SDK installed and Android Studio packages everything for me. Fair point; I don't have Android Studio like I did
last time I used React Native. I'll try that next. If this doesn't work, I give up on React Native for now.

After 5 minutes of building and 99% progress, the build failed. React Native is not for me anymore. I'll try it again
in a few months maybe. I'll keep this public on GitHub so others can read about my struggles and maybe learn from my 
mistakes somehow. And also so I can vent about this project.

## Day 2 | Part 2

I vented to AI about this, and it gave me an idea. I'll try one last fix attempt before I give up for good. It appears
that I have the wrong version of one of my packages. I need to update the package and rebuild again. If this doesn't
work, I know what I want to work on instead of this project, so that's reassuring.

And after 8 and a half minutes...  
**IT FINALLY WORKED!**  
The first thing I notice is that they've changed the template significantly. It no longer
looks slightly dated. It looks very modern, I quite like it! 
Well, I feel like calling it a day now. I'll continue at another time.
