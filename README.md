# cardea

![cardea](https://media.discordapp.net/attachments/824827852763168808/904486519891460126/unknown.png)

goes in `/etc/ssh/sshrc`

IP needs to be set to group subnet

on centos, change ss to /usr/sbin/ss  

discbin path needs to be set

webhook url needs to be set

Note: requires that a central jump host (such as the OSSEC/ELK) server is used for all SSH connections into vulnerable hosts, otherwise you'll get false positives.

uses discbin: https://github.com/thief-adj/discbin
