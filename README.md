# SpringBoard_Settings_Changes_in_Screenshots
So the developers out there - or just the curious (or the impatient and eager) - can look into this instead of going to @hamzasood's Twitter profile to check the any new SpringBoard internal prototype settings that *he* has Tweeted.

After almost four years of hell, I FINALLY have something for you. Screenshots, and a tutorial (I guess) on how you can access the internal SpringBoard prototype settings, but keep in mind, it is **ONLY in the iOS Simulator** (which is not easy for the laymen, and it's kind of a hell of a task, in fact), **NOT an actual iOS device**.
That itself will require a jailbreak (or, at least, partial root read/write filesystem access) to access the internal prototype settings menu.

T'was accessed by loading some files in some directories and subdirectories, and hacking Xcode and the iOS Simulator. Not compatible with an actual iOS device (nor with an earlier version of Xcode, or an earlier iOS Simulator model even) just by opening Settings, going to Developer, enabling both the "Access SpringBoard Settings", and "Access SpringBoard Settings (SIM)" toggles, closing out of Settings, and finally, tapping and holding on the Settings app icon to invoke the menu, like so.

To reiterate: **this was found straight in the iOS (10) Simulator, along with a modified build of AdvancedSettings8** (which was compiled for the iOS Simulator *specifically*, and **only** for the x86_64 archictecture of said iOS Simulator), **a modified Developer Settings bundle, and simject**. Please use the x86_64 iOS Simulator models that come preinstalled with (any version of?) Xcode 8 (like the iPhone 5S, iPhone SE, iPhone 7, etc. models), and not the other models that have the i386 slice (like iPhone 5, etc.) They simply will not launch (as far as I'm aware of :/).

By the way, this was theoretically **not** tested (yet?) to work with the iOS Simulator models lower than iOS 10's Simulators. So, it was not tested with the iOS 7 Simulator, iOS 8 Simulator, or iOS 9 Simulator. And even if it were tested, I doubt that it would show the internal settings menu, as it'd just be prone to a possible SpringBoard crash (or even a possible freeze of the SpringBoard) forcing you to reboot (or just close out of the iOS Simulator and reopening it) after you tap and hold on the Settings app icon to invoke the internal prototype settings).

In conclusion: this is commonly for developers only, it's only ever been tested on iOS 10.0, iOS 10.1, iOS 10.3 Simulators, and you need Xcode, Theos, and simject, plus a few other files that I modified. And it will not work on i386 iOS Simulator (iPhone 5, etc.) models.

I will soon post the recompiled AdvancedSettings8 and the Developer Settings bundle, and all of it's accompanying files for you to download, put in it's appropriate folder locations, and test (provided you have all of the necessary files and things aformentioned), and then you should be good to go.
.
.
.
.
.
.
puppets sing

**Willy WOOOOOONKAAAAA, HERE HEEEE IIIIIIIIIIIIIIIIIIIIIIIIIIIIIIISSS!!!**
