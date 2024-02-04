# 🏡 Aardenne

[💐 Download Zip](https://github.com/ns-studios/Aardenne/zipball/main)

Welcome to Enne's magical Aardwolf plugin garden.

## 🪷 GoAFK

Type goafk <your away message>, and GoAFK will set your title to your AFK message, automatically reply to received tells with customizable messages, and prevent you from disconnecting due to inactivity.

Commands:

* goafkconfig

Shows configuration for the AFK system, letting you set:

    * how long the auto-responder waits before responding to the same person again (in seconds) (default 60).
    * The title to be used when the AFK mode is removed with &ldquo;goafk off&rdquo;.
    * The list of messages that will be randomly picked from for auto-responding.

The messages are separated by a new line, and there are wildcards that can be used in the message. They are:
        * %name%

Your character's name.

        * %target%

The name of the player sending you a tell while you're AFK.

        * %state%

The AFK message you've entered with the &ldquo;goafk <away message>&rdquo; command.

        * %time%

The amount of time that has passed since you turned on the AFK mode, e.g., 2 hours, 1 minute, and 2 seconds ago.

This can be combined into messages such as:

> Hey %target%, This is %name%'s AFK system. They have been %state% since %time%. They'll contact you once they're around again.

Which might result in an automatic reply such as:

> Hey Enne, this is Aily's AFK system. They have been sleeping since 22 minutes and 5 seconds ago. They'll contact you once they're around again.

* goafk

Shows help.

* Written 2022-06-09.

* Published 2024-02-03.
