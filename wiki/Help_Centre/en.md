<!-- TODO: same deal as FAQ. this should be split up into appropriate articles and only written as guides where necessary. right now this page is only useful for people linking directly to sections of it -->

# Help centre

Having trouble with something? We're here to help! Check out some solutions to common issues in the sidebar to the left of your screen.

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
