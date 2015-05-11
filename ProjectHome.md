Various small tools to deal with QuickTime on Windows.

The idea is to show up-to-date, concrete and useful examples of QuickTime on Windows, which seems to be a big secret for some reason. I haven't had much luck in finding information for my own researches so I've had to spend a lot of time groveling through QuickTime docs and fighting build setups. Maybe I can save you some time.

The utilities are:
  * qtping - Dump information about a QuickTime file specified on the command line.
  * More to come as I get them ready...

These examples are primarily for Windows. In **theory** they should work on the Macintosh with suitable massaging. I don't have a Mac available, so you're on your own. You shouldn't have too much trouble though, QuickTime is a Macintosh technology after all!

The programs are compiled with the [Visual C++ 2008 Express Edition](http://www.microsoft.com/express/download/default.aspx#webInstall) (it's free as in beer). You'll need to make a Windows Live account to download and register it. "Enterprise" users should be able to load the solution files as well.

You will need the [Apple QuickTime SDK](http://developer.apple.com/quicktime/download/). You'll probably need to make an Apple developer account to download it.

Some useful documents:
  * [QuickTime Overview](http://developer.apple.com/documentation/QuickTime/RM/Fundamentals/QTOverview/QTOverview_AIntro/Introduction.html)
  * [Getting Started with QuickTime](http://developer.apple.com/referencelibrary/GettingStarted/GS_QuickTime/index.html)
  * [QuickTime Guide for Windows](http://developer.apple.com/documentation/QuickTime/RM/QTforWindows/QTforWindows/C-Chapter/3BuildingQuickTimeCa.html#//apple_ref/doc/uid/TP40000940-BuildingQuickTimeCapabilityIntoaWindowsApplication-DontLinkElementID_9)

Windows command line parsing stinks, so much gratitude to [bsittler](http://xent.com/~bsittler/geocities/) for the use of his my\_getopt library:
<pre>
my_getopt - a command-line argument parser<br>
Copyright 1997-2001, Benjamin Sittler<br>
</pre>

&lt;wiki:gadget url="http://www.ohloh.net/p/329412/widgets/project\_factoids.xml" border="0" /&gt;