September 2019 Update:
Added the optional ability to CC the spam sender. Because "follow-up" spam. You know. Those spammers that continually re-forward the same message to you every week making it look like a legitimate follow-up thread. So now in addition to submitting the spam to SpamCop, you can optionally (and by default) CC the spam sender.

Reporting spam to SpamCop can get to be tiresome. The normal process is:
1) Receive spam
2) Copy the raw message
3) Log into SpamCop.net
4) Paste the message
5) Wait for the verification message
6) Mark the message as spam in Mail
7) Delete the message
8) Click the link in the verification message
9) Submit the spam report
10) Delete the verification message from Mail

Luckily much of it can be automated with Mac Mail and some AppleScripting. The solution I'm posting boils it down to:
1) Receive spam
2) Fire a script via the applescript menu
9) Submit the spam report
As you can see, 7 steps are handled automatically.

Graphic (but dated) instructions at: http://www.webveteran.com/blog/web-related-software/spamcop-deputy/automate-reporting-spam-to-spamcop-net/