# KaffeeSec - SoMeSINT
## TryHackMe OSINT CTF

### Target:
### {Thomas Straussman}

Known usernames:Only found on twitter and reddit as advised to stay in scope of the room
tstraussman - twitter, reddit

Thomas fav holiday: christmas, found in his twitter bio

Thomas birthday: 12-20-1990, found via a reddit post celebrating his 30th birthday on dec 20th 2020

Thomas fiance twitter handle: FHodgelink, found via searching his followers and using the name given in the background info

Thomas twitter wallpaper: budda, found by looking at it lol



### SPIDER
TOOL NAME: Spiderfoot
In this section we use a pyhton powerer internet spider/crawler/scraper/blahblahblah

Once spiderfoot is running on our machine we navigate to its webinterface.

here we start a new scan using what we have: Thomas Straussman and tstraussman

Now we wait, we will filter our results for reddit and twitter as these are what is in our scope.

Results of interest: sfp_accounts, this was as simple as just looking at our scans interface.

Shadowban API: I used a previous writeup to get this flag as the link is no longer available at the time of writing. 




### Connections!!
Advice: reverse image searching, ctrl shift C to inspect meta data

This section is heavily social media intelligence, we are going to pivot to his fiances account.

Where did Thomas and his fiance vacations? Koblenz, Germany found with a scroll through her twitter, and found via a reverse image lookup of the picture posted

When is Francesca's Mother's birthday? Dec 25, found with a scroll through her twitter

What is the name of their cat? Gotank, found with a scroll through her twitter

What show does Francesca like to watch? 90 day fiance, also on her twitter profile





### Turn back the clock...

Now that we have done our twitter digging, we will move to reddit.
The room tells us we will be using the old version of reddit for wayback osint, and the current version as well
"Use the old version (http://old.reddit.com/) for wayback machine purposes
Use the new version (https://www.reddit.com/) for other purposes (later on)"

We are advised to search the waybackmachine on Thomas birthday post:
We discover a comment left by his coworkers reddit account.

What is his coworkers name: It's in the username...

Where does his coworker live? Nuuk, Greenland. Found when opening his reddit page


What is the paste ID for the link we found? (flag format) this is found on Hans reddit page via sifting through previous captures on wayback until a new post appears
"Hi Thomas,

* I know about your little secret, and I know you know. I slipped some paper in your desk the other day, it'll tell you the amount I want in order to stay silent about your little mistress. This isn't a threat, this isn't a fluke, I have proof.
Link: https://ghostbin.com/paste/JENxv/
Password: 1qaz2wsx
Cheers,
H." 

The remaining flags are all found within this email, than the mistress is found within the paste bin
Password for the next link? (flag format): 1qaz2wsx

What is the name of Thomas' mistress? Emilia Moller

What is Thomas' Email address? straussmanthom@mail.com






