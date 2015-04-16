#Better Loopy for YouTube

![Better Loopy Main Screenshot](https://raw.githubusercontent.com/piyushsoni/BetterLoopyForYouTube/master/Documents/BetterLoopy.png)

##Description

If you are like many of us, you'd like to watch/listen to good music videos again and again, on repeat. Unfortunately, YouTube, though being a great music service, lacks an auto repeat feature by default - and hence this extension. It uses YouTube Player API to give you all the awesome features it has! It was once built over the old (and long dead) initiative 'Loopy for YouTube' (http://userscripts-mirror.org/scripts/show/28832) but has come to great extents since then, and adds numerous wonderful features for an interruption free music listening pleasure of the user!

##Features
 - Of course, you can loop just a duration of a video or loop it whole, **right inside YouTube.com!**, seamlessly integrated with it.  
 - YOU choose which features to enable - Show only the loop button, timed Loop bar, next videos or nothing at all! 
 - Send a "looped" video link to your friends (they need to have the extension installed)!
 - Optionally remember the start and/or loop times for a particular video so that it always plays in that time range
 - Shows a counter of how many times you have looped a video. (Hover your mouse on the 'Loop' button)
 - You can also Auto Play all the YouTube videos on ANY webpage one by one, automatically using this on just a click of a button! (Explained below ... )
 - Works in most of the YouTube layouts !!
 - It keeps itself updated, so that you don't have to bother doing that.
 - Optionally loop all videos by default.
 - Works in YouTube's Pop-up and full screen modes as well.
- Works on User channels
 - Customizable shortcuts for the most common Better Loopy Features, with some added shortcuts for common YouTube Tasks 
	 - Alt + L for toggling Loop
	 - Alt + M for Showing the Settings
	 - Alt + P for playing/pausing the video
	 - Alt + N to go to the next video when playing all videos on a page
	 - Enter to go directly to the Start Time box
	 - Press Enter once in the time textboxes to capture the current video time
	 - Press Left or Right arrows in the Time textboxes to move the start or end time backward or forward by a second.
 - Set Maximum number of times to loop a video

##Looping part of a video
Besides the small 'Loop' button below the Youtube video to play it again and again (if you want **only** this, change from the settings), you will also find three text boxes below it. For looping a given video within only a specific time duration(you need that many times don't you?), just write the start time and end times in this format:

minutes:seconds

e.g. out of a 10 minutes video if you want to loop only its part from 1:32 to 8:46 you can do that. Just type these values in Start time, End time; OR press the 'Start'/'End' time buttons to set the current video time; OR just press the 'Enter' key to set the current video time in any of these boxes. If any of them is blank, the default start time is taken as zero and default end time is of course the end of video. 

![Click To Set Time](https://raw.githubusercontent.com/piyushsoni/BetterLoopyForYouTube/master/Documents/ClickToSetTime.png)

##Play All YouTube videos on ANY Page
To enable auto playing of all the Youtube videos (linked or embedded!) present on any webpage of any website on just a click of a button with the help of this script, follow this really simple step:

Just open the settings dialog by pressing 'Better Loopy' link at the top of a YouTube video page (or just press Alt+M on it), and drag the link which says 'Play All' there to your Bookmarks toolbar!

![Drag javascript bookmarklet](https://raw.githubusercontent.com/piyushsoni/BetterLoopyForYouTube/master/Documents/dragbookmark.png)

Now, you can just press this newly created button on any page having youtube videos, and it should play them all in the correct order, one by one, automatically in YouTube!
For example,

If you see some youtube links on a webpage like this:

How to solve a Rubik's Cube:
[Youtube Link Part 1](https://www.youtube.com/watch?v=LcJ-y39GzzQ)
[Youtube Link Part 2](https://www.youtube.com/watch?v=Xfw045MjVDQ)
[Youtube Link Part 3](https://www.youtube.com/watch?v=6DZUS1YsUvg)
[Youtube Link Part 4](https://www.youtube.com/watch?v=FzfebdYt_cQ)

Just press this button (you can try it on this page itself after installing the extension and adding the button!) to see them all automatically in the same order.
If you want to skip any video from the list, just press the "Next>" link. The "next videos to be played" list is just a semi-colon separated list of youtube video IDs and you can add them manually too. For example, in the link http://www.youtube.com/watch?v=LcJ-y39GzzQ, the video id is LcJ-y39GzzQ.
