# 🏡 Aardenne

[💐 Download Zip](https://github.com/ns-studios/Aardenne/zipball/main)

Welcome to Enne's magical Aardwolf plugin garden.

## Mushclient
### 🪷 GoAFK

Type goafk &lt;your away message&gt;, and GoAFK will set your title to your AFK message, automatically reply to received tells with customizable messages, and prevent you from disconnecting due to inactivity.

Commands:

* goafkconfig

Shows configuration for the AFK system, letting you set:

* how long (in seconds) the auto-responder waits before responding to the same person again (default 60). If you're happy with the currently set value, just press enter, escape, or click Don't save.
* The title to be used when the AFK mode is removed with &ldquo;goafk off&rdquo;. If you're happy with the currently set value, just press enter, escape, or click the Don't save button.
* The list of messages that will be randomly picked from for auto-responding. If you're happy with the currently set list, just press escape, or click the Don't save button.

The messages are separated by a new line (inserted by pressing enter), and there are wildcards that can be used in the message. They are:
* %name%

Your character's name.

* %target%

The name of the player sending you a tell while you're AFK.

* %state%

The AFK message you've entered with the &ldquo;goafk &lt;away message&gt;&rdquo; command.

* %time%

The amount of time that has passed since you've turned on the AFK mode, e.g., 2 hours, 1 minute, and 2 seconds ago.

This can be combined into messages such as:

> Hey %target%, This is %name%'s AFK system. They have been %state% since %time%. They'll contact you once they're around again.

Which might result in an automatic reply such as:

> Hey Enne, this is Aily's AFK system. They have been sleeping since 22 minutes and 5 seconds ago. They'll contact you once they're around again.

* goafk

Shows help.

* Written 2022-06-09.
* Published 2024-02-03.

### 🍂 QuitCheck

Type &ldquo;qc put &lt;container&gt;&rdquo; to have the script put items that would be lost when disconnecting into a container, taking them out of containers or off of your keyring as it does. The items are remembered, so typing &ldquo;qc get &lt;container&gt;&rdquo; gets the same items from the container once you connect again, placing them into their original containers/on your keyring.

qc put guitar

qc get guitar

* Written 2022-07-05.
* Published 2024-02-04.

### ⭐ TargetReport

Type &ldquo;trep &lt;channel&gt;&rdquo; to report your current hp, enemy name, enemy hp, zone, and room number to a channel/send as a tell/reply.

trep tell enne

trep ft

* Written 2022-08-12.
* Published 2024-02-04.

## Copyright: Enne, all rights reserved

If you use any of my code, please give credit where credit is due.

For any bugs, suggestions, ideas, send a tell or a note to enne on Aardwolf, or make an issue here.

The scripts are provided "as is" and without warranties of any kind, whether expressed or implied. Enne disclaims all warranties, including but not limited to, the implied warranties of merchantability, fitness for a particular purpose, and non-infringement.

Any harm, damage, or liability arising from the use of Aardenne is solely the responsibility of the user. Enne shall not be held liable for any direct, indirect, incidental, special, or consequential damages resulting from the use of the scripts.
