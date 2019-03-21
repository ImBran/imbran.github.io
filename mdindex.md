## Learning Markdown
###### March 19, 2019
I have been wasting too much time on html/css on this website so I will be learning Markdown using [Dillinger Online Markdown Editor](https://dillinger.io) so I can post more rapidly and not get caught up in the maintanence or style of this otherwise content and featureless page. This blog is intended to document my progress and keep me focused on my current projects rather than become a project on its own. 
___
## Access  TV4/4k Filesystem Information
###### DEC 9, 2018 • 3 MIN READ
The Apple TV has been one of my staple Apple Products every generation of since its inception in 2006, and quite frankly its the only streaming device that I would recommend to anyone that has at least one apple product. I use it as a streaming device in two rooms for TV and also it provides my house with wall to wall music using Airplay to all of my TVs.

To this day my /r/AppleTV posts have been my most successful on reddit including one about the Apple TV Secret Menu Options. Most of these “secret menus” are for development and trouble shooting but some of the information stored should be displayed such as how much storage is available or used.

The new Apple TV 4/4k has been available in 2 storage sizes, 32GB and 64GB since its announcement in September 2015.  It is understood by owners that the space in the Apple TV is very hard to fill being a service streaming and cloud retrieving device, the 64gb in particular being ostracized for being too big and impossible to fill. In any matter, people love to have control over their devices and power users want to be able to view the filesystem information. Now, there is none of this information openly displayed in the settings menu but with a little finesse, you can view all of the system analytics data including the used and available storage in a few simple steps.

 **_You will need:_** 
 Apple TV 4/4k with Siri remote, an airdrop capable device on the same network as your Apple TV, .tar extraction capability (Mac computer or PC with extraction software).
 
### Run Analytics
    Hold down the play/pause and volume down buttons for ~10 seconds and release.
System Analytics will run in the background and prompt you when it is completed.

### Extract tarball
You can export the data tarball immediately to a device with AirDrop (recommended) or it will be saved to be shared later in Settings/General.Privacy/Analytics Data named sysdiagnose... 

### Extract the .tar.gz.
Finder window showing contents of extracted 'sysdiagnose_[DATE_TIME_Apple_tvOS***].tar.gz
### Open disk 
    Inside of the extracted folder open "disks.txt".
___
## Windows Service Stripper
###### SEP 22, 2018 • 2 MIN READ
Well, it’s been a few years since I’ve last used Windows so I thought I’d give it a whirl again in a VM instance. Thanks Oracle for Virtual Box https://www.virtualbox.org for an amazing free and Open Source virtualization solution.

I’ve installed Windows 10 Enterprise edition and a few things made me happy upon first sight of the desktop, and a lot made me sigh or cringe. First off the metro interface has taken a welcomed back seat. The settings app has finally been streamlined, the context menus are no longer opened on the bottom 10% of the screen, and the start menu can be right clicked to open file explorer and administrative tools. The start menu can be customized by deleting all of those ugly live tiles as well as Cortana can finally be disabled very easily without castrating the system search settings.

Windows is still home for a lot of packaged bloat, however. Even the Enterprise edition comes with Xbox management and integration services and tons of other useless features for people who just want a bare bones installation.

I have released [Windows Service Stripper](https://github.com/ImBran/Win10SS) as a quick and easy tool to help disabling system services, removing unwanted application packages and prevent some of its telemetry services. This tool is safe for private but not intended to be used commercially. This BAT is designed with pro and novice users in mind and requires administrative rights to run. The BAT executes in a CMD.exe window and initiates each step chosen by the user and verified through PAUSE commands. It creates a folder in /ProgramFiles with a .log file records the date and time of each commands last run. There is also an option to enable GOD MODE in C:/. This a Windows Custom folder where a shortcut for all of its built-in Administrative Tools and their descriptions for quick and easy access. WSS is available for download/pull on my GitHub projects page.
___
##  iPhone, a PC Replacement
###### Sep 18, 2018 • 3 min read
For two weeks this summer I did a stupid thing. I used my iPhone 7 as my daily workhorse PC while I was in between MacBook purchases, and I gotta tell ya, it wasn’t that bad. Now, which should come to no surprise, I am an apple fan. I have owned a Mac for over 14 years. But before this little experiment I would have doubted that anyone can replace a proper PC with any iOS device especially an iPhone. After my experience however, I am optimistic about the future of computing and how a unified computer experience is closer than I expected, with iOS. Here’s what happened.

Recently I went through little bit of a setup dilemma. I sold my 2017 15” MacBook Pro after the Keyboardocolypse and bought a 27” iMac. I was dissatisfied with that purchase so decided to return it and temporarily use my phone as my daily driver PC before ordering a brand new surprise 2018 quad core 13” MacBook Pro. During this time, I had to limit my workload a bit but for 2 weeks I went without a real need for a full powered computer.  I used iOS text editors, purchased the 200GB iCloud storage plan for $2.99/month and used a cheap Anker bluetooth keyboard I had laying around. This worked for the first day until the strain of staring at my *small iPhone 7 plus screen for hours became too much of a hassle, so I began AirPlaying my iPhone display to my TV and while it being stretched to fit the bigger screen wasn’t ideal, it suited my needs as a temporary fix.

After a few days it felt usable. I enjoyed having everything I needed, personally and professionally, on my hip. The ability to rely solely on services (iCloud, AirPlay, AirDrop, AirPrint) was a change for me. I’m someone who likes having a music library and not relying on streaming music services. I barely used airplay and airdrop. I even already owned a monochrome AirPrint enabled printer but only powered it on when I needed it. Just as cutting the cord to a cable TV service changes your relationship with TV, going from a classic desktop/laptop setup to an iOS device comes with some disadvantages. But if your choosing to go all-in, it’s important to welcome all of its advantages and use them to their full potential.

So is it time to ditch the desk? My answer for most professionals is no. But if you are someone who wouldn’t mind the limitations of being an early adopter and willing to change your relationship with a PC, then go for it.
___
brandonmarcelle.com
[GitHub](https://github.com/ImBran) [Vsco](https://vsco.co/brankm) [Lobste.rs](https://lobste.rs/u/Bran)
<me@brandonmarcelle.com> 
[Keybase PK](keybase.html)