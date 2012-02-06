Reporting spam to SpamCop can get to be tiresome. The normal process is:
1) Receive spam
2) Copy the raw message
3) Log into SpamCop.net
4) Paste the message
5) Wait for the verification message
6) Mark the message as spam in Mail
7) Delete the message
8) Click the link in the verification message
9) Wait for spamcop.net's nag screen to go away
10) Submit the spam report
11) Delete the verification message from Mail

Luckily much of it can be automated with Mac Mail and some AppleScripting. The solution I'm posting boils it down to:
1) Receive spam
2) Fire a script via the applescript menu
9) Wait for SpamCop.net's nag screen to go away
10) Submit the spam report
As you can see, 7 steps are handled automatically.

Graphic instructions at: http://www.webveteran.com/blog/web-related-software/spamcop-deputy/automate-reporting-spam-to-spamcop-net/