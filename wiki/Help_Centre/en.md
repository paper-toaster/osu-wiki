<!-- TODO: same deal as FAQ. this should be split up into appropriate articles and only written as guides where necessary. right now this page is only useful for people linking directly to sections of it -->

# Help centre

Having trouble with something? We're here to help! Check out some solutions to common issues in the sidebar to the left of your screen.

---

## Online features

### I can't sign in or connect to osu! at all!

**Ensure that osu! can properly access the Internet through any firewall or anti-virus suites you have installed on your computer.**

Read on to learn about a few ways of allowing applications to have Internet access through several common anti-virus suites!

#### Allowing a program through Windows Firewall

**On most Windows installations, Windows Firewall will be the default firewall software.**

To make sure osu! can access the Internet, we're gonna need to allow it to communicate through Windows Firewall. You can check and add osu! to the program list by doing the following:

1. Open the Start menu.
2. Type `allow an app` into the search bar within the Start menu.
3. You should see a Control Panel match titled `Allow an app through Windows Firewall`. Click it.
4. A panel with a large list of applications with two checkboxes beside them will open. Click on any application, and then hit the `O` key. The list will scroll down to all applications beginning with "o".
5. Look for `osu!` or `osu!.exe`.
6. If neither are present, click `Allow another app` at the bottom of the panel and search for your osu! installation directory, and choose `osu!.exe`.
7. Make sure both `Private` and `Public` checkboxes are ticked. Click `OK` to save your settings. And then try opening osu! again.

#### Allowing a program through AVG Firewall

Please consult AVG's [official knowledgebase entry on the topic](https://support.avg.com/SupportArticleView?l=en&urlName=Allow-application-in-AVG-Firewall) for detailed instructions on how to do this.

#### Allowing a program through Kaspersky Security Center

Please consult Kaspersky's [official help article](https://support.kaspersky.com/7834) on adding applications to the Trusted Zone for detailed instructions on how to do this.

#### Allowing a program through McAfee

Please consult McAffee's [official knowledgebase entry on the topic](https://service.mcafee.com/webcenter/portal/cp/home/articleview?articleId=TS100813) for detailed instructions on how to do this.

#### I've added osu! to my firewall but I still can't connect to the server!

**If this happens, we'll need extra information from you to help sort this out.**

If you are still having issues connecting to our game servers, please submit a support ticket by sending an email to [accounts@ppy.sh](mailto:accounts@ppy.sh). The following information below will help us resolve your issue quickly:

- A trace route output log from the command `tracert` for the servers `cho.ppy.sh`, `osu.ppy.sh` and `m1.ppy.sh` (see below for instructions)
- The `network.log` file from the `Logs` folder in your osu! installation directory

##### Running a trace route to troubleshoot connection issues

**A trace route will help us detect exactly where the problem is between you and our servers.**

*Note to less tech savvy users: to run a command in the Command Prompt, simply type the given name of the command into the window, and press `Enter`.*

You can perform a trace route by opening the Command Prompt and running the command `tracert`.

To open the Command Prompt, press and hold the `Windows` key and press `R`, then type `cmd` and click `OK`. For more information, see this [Windows knowledgebase article.](https://support.microsoft.com/en-us/kb/314868).

You can then type the trace route command into the console. For example, the command `tracert cho.ppy.sh` will track how your computer connects to the game server over the Internet. But please keep in-mind that tracing routes takes a little bit of time (sometimes upwards of a minute or more depending on your connection!).

We will need the results from a trace route command for the servers `cho.ppy.sh`, `osu.ppy,sh` and `m1.ppy.sh`.

*Notice: in many terminals and command lines like the Command Prompt, the `Ctrl`+`C` shortcut does not work the same as it does on most modern computers. In most instances, a right click will copy the text with no toolbar or dropdown menu appearing.*

To copy the results of the command, simply click and drag from the bottom of the output all the way to the top so that the information turns white, then right click to instantly copy it to your clipboard.

#### I changed my settings, and now I can't start osu!/osu! is freezing!

**Resetting osu! back to its default settings will fix this in most cases.**

Follow the steps below to restore osu! to its default settings:

1. Hold down the `Shift` key on your keyboard.
2. While holding `Shift`, double click the osu! icon on your desktop.
3. Continue holding `Shift` until you see the osu! recovery dialog prompt.
4. When the `osu! configuration` dialog opens, click the `reset settings` button.
5. If you still aren't having any luck, open the dialog again and click `repair osu!`.

#### I became a supporter, but my name isn't yellow in-game!

**You will always appear white to yourself on the in-game client. Other users will be able to see your glorious yellowness, though!**

This helps to identify your own messages from everyone else's. There's no option to disable it at this time, sadly.

---

## Performance

### osu! is making my computer overheat/my computer fans are really loud when I play osu!

**The easiest way to fix this is to change your frame limiter settings.**

To check what your frame limiter is set to, do the following:

1. Open osu!.
2. Enter the Options menu (or press `Ctrl` + `O`).
3. Type `frame` into the quick search to bring up the frame limiter options.

If your frame limiter is set to `Unlimited`, you may notice a significant improvement by changing it to one of the other three options.

`VSync` will run the game at a refresh rate equal to that of your main monitor, while `Power Saving` and `Optimal` will run the game at twice and eight times your monitor's refresh rate, up to 960Hz.

We recommend using `VSync` in situations where heat is an issue.

You may also wish to look into utilities that allow you to control the speed of your CPU and GPU fans manually.

### My PC reboots while playing osu!

**Most of the time, this is due to the overheating of one or more of your computer's components, usually your graphics card or CPU.**

To figure out what's causing this, we recommend you use a GPU/CPU temperature monitor and keep an eye on it as you play osu! in the background. We reccomend using [Piriform Speccy](https://www.piriform.com/speccy).

If you notice either your GPU or CPU temperature exceeding values of 90°C (194°F), your computer is running very hot and dangerously close to most automatic shutdown thresholds.

#### My computer isn't overheating, but the game still causes my computer to reboot!

**The most common cause of forced restarts—aside from overheating issues—is sound card problems, followed by malfunctioning peripherals attached to your computer.**

Old sound card drivers or software can cause problems with osu!, but this is not an issue for most people. Try updating your sound card or motherboard drivers if you think this may be the issue.

You may also wish to try removing some of the peripherals attached via USB to your computer, especially if they interact with sound in any way. Headphones or USB sound cards can sometimes cause problems if they, or the port they are in, begins malfunctioning.

#### It's still happening!

If none of this helps, please send in a support ticket to [accounts@ppy.sh](mailto:accounts@ppy.sh) with more information on the issue. We ask that you please remember to include your computer's technical specifications, model (where appropriate), and any other information you think may help us discern the cause of your problem.

### I can't hold more than a few keys at once while playing osu!mania

**This issue may be due to a hardware issue common to most keyboards called "ghosting".**

Ghosting is a somewhat complex topic, but essentially boils down to issues with the way your keyboard is made that prevents it from sending more than a few keys down at once from certain places on the board.

Most newer keyboards will allow up to 6 keys to be held down at once, albeit in random combinations.

You can test your keyboard's ghosting limits by using [drakeirving's Anti-Ghosting utility](https://drakeirving.github.io/MultiKeyDisplay).

While the Ranking Criteria for osu!mania tries to alleviate the issue of ghosting by not allowing more than 6 notes to be active at any one time, you may encounter this issue if your keyboard is older.

The only true solution is to purchase a keyboard that can support more concurrent keypresses. You may wish to look for a feature known as *n-key rollover* (*NKRO*). NKRO keyboards do not have issues with ghosting for the most part, but are usually expensive.

### My cursor goes crazy whenever I try to play osu!

**The most common cause of this is having your in-game mouse sensitivity set too high.**

Jumpy, erratic movement is a prime example of this, particularly if you are using a tablet.

Setting the in-game sensitivity to 1.0x (which is default) will fix this in most cases, but may leave your cursor feeling sluggish. We suggest enabling *raw input* in the game options and using the drivers for your peripheral of choice to alter sensitivity.

If you're using one, you might want to adjust the DPI setting of your mouse, too. Higher DPI settings provide more accurate positioning to the game client and may smooth out any jitters.

We also suggest ensuring your peripherals are clean and free from dirt or debris. A string of hair or bit of dust in front of a mouse's optical sensor can do very strange things to the way a cursor moves.

#### What is raw input, and how do I turn it on?

**Raw input forces the game to use a cleaner and more direct means to access the information from your peripherals. This generally increases the accuracy of the output from the device.**

That feeling of increased "accuracy" from turning on raw input is usually because your mouse will no longer "accelerate." Mouse acceleration is basically a way of making the cursor move faster to travel a farther distance (i.e., accelerate) when you speed-up your mouse movements. Most people like this feature when using a computer normally, but when playing osu!, it can cause unpredictable, and jumpy movement. 

*Notice: If you're using a tablet, turning on raw input may cause the cursor to be stuck in the corner of the screen. This is due to the way tablets are designed, as they use absolute positioning (unlike computer mice, which use relative positioning)*

To enable raw input, do the following:

1. Open osu!.
2. Enter the `Options` menu or press `Ctrl` + `O`.
3. Type `raw` into the quick search to jump straight to the option.
4. Click the `Raw input` radio button.

### I'm playing from a tablet and my cursor feels too slow!

**You can solve this problem by defining a smaller tablet area for your device.**

On most Wacom tablets, this is done via the `Mapping` tab of the `Wacom Tablet Properties` application.

![Wacom Tablet Properties screen showing Mapping options](img/Tabarea.png "Interface for changing tablet area on Wacom devices")

You'll need to consult your tablet's manufacturer to find out how to set your tablet area for your particular peripheral.

All osu! branded tablets support raw input by default, and may have their sensitivity easily adjusted on the fly by using using the mouse sensitivity slider. Unfortunately,<!--as of ____,--> osu! branded tablets are no longer being officially sold or manufactured.

### My songs list keeps scrolling!

**This is usually due to a faulty input device connected to your computer. Try unplugging any controllers or joysticks.**

Applications which emulate or change keybindings such as *Xpadder* or *X-Mouse Button Control* may also cause these issues. Try disabling them if you use them for other games.

This can also happen due to issues with the numpad keys, as they can be used to scroll the song selection list. Pressing the `NumLock` key to disable the numpad and then pressing either `9` or `3` on the numpad will fix the issue. You should also check for any jammed or damaged buttons on your peripherals while doing this.

#### I downloaded a Beatmap Pack but osu! is always trying to "repair" the file!

**You'll need to extract the pack into your `Songs` folder.**

Most beatmap packs come in a `.rar` file format, which means they are a compressed archive of beatmap files. You'll need to extract them using your utility of choice. (We recommend [7-Zip](https://7-zip.org)) to your Songs directory first.) <!-- do we though? WinRar is widely recognized to be the first option for unzipping files afaik, but YMMV (remove comment before merging) -->

Once all of the `.osz` files within the pack are in the `/Songs` folder, hitting `F5` at the song selection menu will refresh the game's beatmap cache and load your new songs into osu!.

---

## Website

### I haven't received a reply to my support ticket, and it's been over 2 weeks!

**The vast majority of the time, this is due to a high number of tickets coming into our system at once.**

You can always send a single reply to your currently open ticket asking about the state of your case, but make sure not to do this more than once or twice a week. You can also contact us on Twitter at [@osusupport](https://twitter.com/osusupport) to ask about your ticket.

In rare circumstances, support tickets from chronically offending users may be deliberately ignored. Although the team will **always** tell you when they'll no longer be responding to you. If you haven't received a notification like this, you don't need to worry about it!

### My user page contents are missing!

**This can happen if your user page had inappropriate content on it, as defined by our [Community Rules](/wiki/Rules).**

In such cases, you may open up a ticket with the support team by emailing [accounts@ppy.sh](mailto:accounts@ppy.sh) and discussing your situation with them.

If at any point you are in doubt as to whether or not something is appropriate for a userpage, you can message any of the members of the [Global Moderation Team](/wiki/People/Global_Moderation_Team) with what you plan to put up, and they will let you know if it is okay.

### Can I completely block another user from contacting me?

**Yes, absolutely!**

In the event that another user is harassing you via private messages either on the forums or via the game client itself, there are a few steps that you can take to filter out their messages.

#### Blocking a user from contacting you in-game

**To block a user from sending you messages in-game, simply add them to your ignore list.**

1. Go to `Options` (or press `Ctrl` + `O`).
2. Type "ignore" to filter the options listing to the "Chat Ignore List" section.
3. Add the offending user's username to the list, separating each new user with a space, and replacing any spaces in their name with underscores. (E.g., a user called `The Gatekeeper` would be typed as `The_Gatekeeper`).
4. You're done!

After doing this, you'll no longer see public chat messages from any users on that list, nor will you receive private messages from them.

If you want to ignore highlights, private messages, or public messages, in specific, you can simply append respectively `@h`, `@p`, `@c` to their username. For example, `The_Gatekeeper@c` will ignore the user's messages in public channels. It's possible to combine these as well: `The_Gatekeeper@ph` will ignore highlights and private messages, but leave public messages visible.

#### Blocking all non-friends from sending you private messages in-game

If you wish to prevent anyone not on your friends list from sending you private messages, do the following:

*Notice: moderators are not affected by this functionality and can always privately message you. If you feel a moderator is harassing you in spite of this, you should contact [our support team](mailto:support@ppy.sh) immediately.*

1. Click the `Options` menu button in-game (or press `Ctrl` + `O`).
2. Type "block" to filter the options listing to the "In-game Chat" section.
3. Toggle the setting on by clicking `Block private messages from non-friends`.
4. You're done! Users who aren't on your friends list can no longer contact you.

#### Blocking public forum posts from a user <!-- TODO: this part needs to be rewritten for the current website, "foes" is no longer available on the old one -->

*Notice: the Foes list is currently unavailable on the new website.*

**To naturally hide most public forum posts from a particular user, add them to your Foes list via the UCP.**

1. Head over to the [foes list setting in the UCP](https://osu.ppy.sh/forum/ucp.php?i=zebra&mode=foes) and simply add their username to the list as pictured.
2. Click submit.
3. You are done! Most forum posts from that user will no longer be visible to you; it will be as if they were never there. Other users quoting their posts will still be visible, though.

#### Prevent any new forum private messages from reaching you

Go to your [account settings](https://osu.ppy.sh/home/account/edit) and click `block private messages from people not on your friends list` in the Privacy section. Private messages from users in your friends list will still reach you.

#### What if I'm still having problems with a user after blocking them?

**Never fear, for our support staff is here!**

If a user is still harassing you via other means, or using their friends or someone else to circumvent your effort to block them, please send us an email at [support@ppy.sh](mailto:support@ppy.sh).

Make sure to include any chatlogs or other evidence in the email, and our support staff will look into your case and see it sorted for you.

### What are these "user pages" that I see on other players profiles?

**User pages are special profile elements that all players with a [supporter tag](https://osu.ppy.sh/home/support) get access to. They can contain whatever you like: pictures of your achievements, your beatmaps, basically anything you wish!**

Players with a supporter tag are given the privilege of editing their very own page to display on their profile! User pages may contain anything you like, so long as it follows the [Community Rules](/wiki/Rules)!

Even if your supporter tag happens to run out, your user page will **still remain visible** and you'll still be able to edit its contents.

### Do I need to use my email address to register?

**Yes. We require your email address to send you password reset requests and verification codes when needed.**

If you have trouble connecting via the game client, please check your firewall and anti-virus settings to make sure osu! isn't being blocked.

If you ever lose your password or cannot access your account, your registration email is our first point of contact with you.

### Why are the statistics in my user profile page wrong?

**You might be looking at your stats for another game mode! The website defaults to showing your scores for the mode you last played.**

If you've been inactive for a long time, and your statistics are shown wrong, simply play a few maps to display them again. Inactive users may have their scores hidden to keep the rankings fresh.

---

## Installation and Registration

### Installation

Main Page: [Installation](/wiki/Installation).

#### How do I download osu!?

**Simply click `Download` found at the center of the [official osu! website homepage](https://osu.ppy.sh/home). You may also find the link through the `home` dropdown section found at the navigation bar on any page.**

Alternatively, [click here](https://osu.ppy.sh/home/download) for a direct link to the download page.

### Registration

Main Page: [Registration](/wiki/Registration).

#### Where do I register for osu!?

**Download osu! [here](https://osu.ppy.sh/home/download), then run it. The game will prompt you with a section where you can create an account.**

Make sure you provide an email address you have control over. This is used to reset your password and send verification emails when needed. **Do not use a throwaway email.**

---

## Beatmapping and Editor

### How do I upload/update my map?

**You can do this through the in-game editor.**

To upload your beatmap, go into the editor and hit `File` > `Upload Beatmap`.

This will make your beatmap available for others to download on the website and create a dedicated thread for discussion. Updating a map is the same process for a map that has already been uploaded.

Each user has a limited number of maps they can simultaneously upload. Leaving a map inactive for a month (by not updating it or not posting in its thread) will send it to the Beatmap Graveyard. To update a graveyarded beatmap, you'll need to revive it first.

### The editor is telling me that the beatmap I'm trying to submit isn't mine!

**This can happen if the creator of the beatmap is not properly set within the beatmap files.**

In the editor, click `File` in the menu, then `Open .osu file in Notepad`. Check the line `Creator:` and make sure that it's set to your exact username, capitalization included.

If it isn't, manually change it for every difficulty in your set, reload the map, and you should be able to submit it.

#### I'm an osu!supporter, but I don't have 10 pending slots!

**The number of slots available depends on the number of Ranked maps you have.**

By default, every user has **2 pending slots**. 1 slot is added for every Ranked map the user owns, up to a total of 8 slots. Being a supporter grants 2 additional slots, from 4 (without Ranked maps), up to a total of 10.

#### How can I delete my map?

**The team does not take requests to manually delete uploaded beatmaps.**

You can delete your beatmap yourself by waiting for it to decay to the beatmap Graveyard, which it will do so after a month without updates.

Once your map is in the Graveyard, you can delete it yourself by going to it's beatmap page, clicking the `Discussion` button (which will bring you to its forum page), and then clicking the `Delete` button that appears next to the beatmap link.

---

## osu!store and Merchandise

### osu!keyboard

#### How do I configure the osu!keyboard?

**You can use the osu!keyboard configuration utility, available from [this link](https://puu.sh/l6urN/4b6bc800f2.zip).**

Simply extract it to anywhere on your computer, and run the executable!

The rest should be self-explanatory. But if you have any further issues, please feel free to submit a ticket to [support@ppy.sh](mailto:support@ppy.sh) detailing your problem.

#### The LEDs on my osu! nono keyboard aren't working!

**There are 2 common reasons why the LEDs may not be working: corrosion between the LEDs and the mainboard, or—in certain circumstances with earlier models—faulty LEDs.**

Please contact [store@ppy.sh](mailto:store@ppy.sh) for further inquiries.

##### How do I tell if my LEDs have corrosion on them?

**Rubbing the base of the LED connectors with a small square of aluminium foil will remove most of the residue caused from corrosion.**

Corrosive residue usually appears to be blackish-grey, or may appear as strange stains on the metal. Removing this residue may restore your LED to working condition. If it does, you'll know how to fix it next time!

### osu!tablet

#### My osu!tablet has stopped working/does not work at all!

**This can be tricky to troubleshoot since the osu!tablet is a two-unit system (tablet and pen).**

Given that the osu!tablet is a two-unit system, it can be difficult to tell which unit is experiencing issues when things go wrong.

##### Checking for issues with your tablet device

**Follow these steps to check if your tablet device is functioning normally.**

1. Safely remove osu!tablet from your system and unplug the cable.
2. Gently plug the cable back into a USB slot on your system.
3. If the tablet is functioning, the light slot on the face of the tablet will flash green momentarily then fall dark. This is normal behaviour.

If the tablet's light doesn't flash, try using a different USB cable, as the ones included with the tablet can sometimes be damaged during transit or after extensive use.

Please contact [store@ppy.sh](mailto:store@ppy.sh) for further inquiries.

##### Checking for issues with your pen device

**Follow these steps to check if your pen device is functioning normally.**

- Unscrew the grip from the body of the pen, exposing the battery on the inside.
- Remove the AAA battery from the pen.
- Replace the battery with a brand new AAA battery. **Make sure to verify that the new battery functions in another device first.**
- Ensure that the battery's positive (`+`) and negative (`-`) ends are appropriate in the pen. There are markers on the device that display marks telling you which end goes where.
- Screw the grip back onto the pen.
- Depress the button on the back end (eraser end) of the pen until it clicks.

If your osu!tablet is functioning properly, placing the pen near the tablet will make the cursor on your screen move.

Please contact [store@ppy.sh](mailto:store@ppy.sh) for further inquiries.

### osu!go

#### My computer doesn't recognize the osu!go when I plug it in!

**This is a known issue with one of the very first shipments of the *osu!go* USB sticks. It comes down to the device not being formatted in a manner that works with all PCs.**

Despite how complex this may sound, it's actually very easy to fix.

But you'll first need to download the package containing the osu!go default files and save it somewhere on your computer. You can download those files [here]((https://assets.ppy.sh/store/utilities/osu!go.zip))

##### Formatting the osu!go under Windows

**Follow these steps to prepare your osu!go device under Windows.**

*Warning: **While in the Disk Management view, make sure to follow the instructions *VERY* closely and *ONLY* apply them to the osu!go device.** You can potentially lose data if you fiddle around in this dialog.*

1. Open the Start menu.
2. Type `disk management` into the search bar. This will bring up the `Create and manage hard disk partitions` section of the Control Panel.
3. Check to see what state your computer recognizes the device as being in. Continue to the sections below and the follow the instructions that apply to you.

#### The osu!go device is present, but in a "RAW" state

**This will appear like [this](https://puu.sh/nktuJ/05791b6fc1.png) in the Disk Management dialog.** <!--shouldn't this be a photo and not a link to a photo?-->

To fix this, ensure you have the osu!go device selected, and right click on the RAW partition and select the `Format` option. Choose either `NTFS` or `exFAT` under the `File System` dropdown.

*Note: `exFAT` will work with most devices, but is slightly slower.*

#### The osu!go device doesn't show up in Disk Management at all

**In this case, you'll need to partition the device from scratch.**

Please follow [this guide](https://staging.tails.boum.org/doc/first_steps/reset/windows.en.html) for details on how to do that.

#### I've reformatted the osu!go device and it now shows up in Disk Management

**You're almost done!**

Unzip the archive we asked you to download earlier (`osu!go.zip`) into the osu!go drive, and then you'll be done!

#### None of this worked!

If you encounter any issues with this process, please send an email to [store@ppy.sh](mailto:store@ppy.sh), and we'd be happy to help you out.

---

## Troubleshooting

### What are "log files" and how do I make them?

**Log files are detailed recordings of what the game client is doing at any given point in time. We can use them to help determine what's causing your issue.**

These files are extremely handy to have and can make solving even complicated issues trivial.

If a support team member has asked you for these logs, you can learn how to get them below:

1. Open osu!.
2. Go to the `Options` menu by clicking the button on the main menu (or hitting `Ctrl` + `O` on your keyboard).
3. Type `release` into the quick-search bar. This will take you to the current release stream your client is using.
4. Make sure its is set to either `Beta` or `Cutting Edge (Experimental)`. We recommend `Beta` for the best chance of stability in this situation.
5. Restart the game client if you made any changes to the release stream to apply them.
6. Reopen the game, enter `Options`, and click `Open osu! folder`.
7. Find the `Logs` directory in the window that opens.
8. Select the log file required (the support representative will tell you which), and attach it to your ticket or upload it to a public filesharing service.

### What is this "Bancho authentication error" I keep receiving?

**This typically happens when there are networking issues between you and our servers.**

There are a few things you can try in order to resolve this issue.

#### Have you entered your password correctly?

**This is the most obvious one.**

If you've forgotten what your password is, you can use the [password recovery page](https://osu.ppy.sh/home/password-reset) to recover access to your account.

#### Are you using any proxy servers or VPNs?

**Disabling these before attempting to connect again will likely fix your issue.**

Some VPN providers and proxy servers simply don't work with osu!, for whatever reason.

#### I'm still getting the error!

**We'll need a `network.log` file from you to figure out what's going on if neither of the above solutions work.**

Check out the article a section above on how to get a log file to send to us.

In rarer cases, you might need to contact your ISP to inquire about these problems. Certain ISPs have historically had issues connecting to osu!, usually due to poor routing.
