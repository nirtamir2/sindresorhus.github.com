---
title: Command X
subtitle: Cut and paste files in Finder
pubDate: 2023-04-30
platforms:
  - macOS
appStoreId: 6448461551
---

Cut and paste files and folders in Finder using Command+X and Command+V. Without this app, you have to first copy (Command+C) and then remember to move (Option+Command+V).

[Review by Softpedia](https://mac.softpedia.com/get/System-Utilities/Command-X.shtml)

Known limitation: You cannot cut the name of a file when editing a filename in Finder. There is no way for the app to work around this.

<br>

### Frequently Asked Questions {#faq}

#### I have a feature request, bug report, or some feedback

[Send it here.](/feedback?product=Command%20X&referrer=Website-FAQ)

#### Why? I can already use `Option+Command+V`

- It's more logical to cut & paste than copy & move.
- Consistency and muscle memory benefits if you also use Linux or Window.

#### The app does not show up in the menu bar

macOS hides menu bar apps when there is no space left in the menu bar. This is a common problem on MacBooks with a notch. Try quitting some other menu bar apps to free up space. If this does not solve it, try quitting Bartender if you have it installed.

#### The app does not work {#not-working}

First, make sure you pressed <kbd>Command+X</kbd> and not <kbd>Command+C</kbd>.

Then try enabling the setting “Use more reliable way of handling Command+X”.

To make sure you used the app correctly. Try this: Select a file in Finder, press <kbd>Command+X</kbd>, change to a different folder, press <kbd>Command+V</kbd>. The file should have been moved to this new folder.

To help me figure out the issue, press <kbd>Command+X</kbd> and <kbd>Command+V</kbd> in Finder, click the “Copy Debug Info” button in the Command X menu bar menu, and then [send the debug info to me](/feedback?product=Command%20X&referrer=Website-FAQ), including a short explanation of what didn't work.

#### Is there any risk of data loss if I forget to paste?

No. The files are not touched until you paste. If you don't paste, the files just stay in place.

#### Can I move files by clicking the “Paste” menu item?

No, you can only use the keyboard shortcuts. The app works by overriding the original keyboard shortcuts. There is no way to override the Finder menu items.

#### Can it make the cut files in Finder have less opacity?

This is not possible. The app works by overriding some key combinations. It doesn't and cannot modify Finder in any way.

#### It does not work when I try to paste directly to an expanded subfolder shown in its parent folder

This is a Finder bug. You can reproduce it even without Command X by selecting the file to move, pressing <kbd>Command+C</kbd>, selecting the destination folder, and then pressing <kbd>Option+Command+V</kbd>.

#### I am not able to cut text when editing a filename in Finder

This is a known issue that is unfortunately not fixable. The app works by overriding the normal cut keyboard shortcut when Finder is active, which also affects cutting text in a filename. There is no way to differentiate between cutting a file and cutting text in a filename in Finder.

#### Where can I find the changelog?

Go [here](https://apps.apple.com/app/id6448461551) and click “Version History”.

#### Can you localize the app into my language?

I don't have any plans to localize the app.

<br>

### Non-App Store Version

A special version for users that cannot access the App Store. It won't receive automatic updates. I will update it here once a year.

[Download](https://dsc.cloud/sindresorhus/Command-X-1.0.6-1684086547.zip) *(1.0.6)*

*Requires macOS 13 or later*
