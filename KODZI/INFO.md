Kodzi Kodi: The Fastest Way to Install Any Addon!


The new Kodzi Kodi enables a super simple way to install other addons and repositories really fast. Reduce the number of sources you need to add in your File Manager or setup Kodi builds really fast with Kodzi.

Kodzi is completely safe and reliable. It is coded to pull out the Kodi repository zip file out of any URL. That means that if you use any of the install guides on our website, you can simply copy and paste the URL into the Kodzi Kodi addon and quickly install the repository without worrying about any of the other steps.

Below is the ultimate guide to what Kodzi is, how to install it, how to use and configure it, and tips for making things quick.

Kodzi Features

The Kodzi Kodi addon contains the following features:

    Install repositories from most websites as long as your URL has a clickable zip file included.
    No need to enter in http/https. Just enter the website as you would in a web browser
    GitHub Clone (gc) and GitHub Tree (gt) support, explained below
    Create a list to bulk install repositories fast in Kodzi

If you are sick of having so many different sources in your File Manager, then the Kodzi Kodi addon will simplify how many sources you heed.

Not bad huh?

Let’s go through the install guide for run down of the addon first and then underneath that are a bunch of tips and tricks to help you set things up.

Kodzi Kodi Layout

When you open the Kodzi addon, you’ll see the following options:

    Enter Website or GitHub URL – Enter the address of any website or GitHub URL containing the repository zip file.
    Enter Lists URL – Enter in the address of a List URL to quickly install multiple repositories
    Installed Addons – Opens your Kodi installed addons folder
    System Settings – Opens your Kodi system settings

 
How to Use Kodzi Addon

At a basic level, simply click the Enter Website or GitHub URL option from the main menu of the addon. A popup will come up asking you to enter in the URL of a Kodi Repository location.

How to Use Kodzi Addon

At a basic level, simply click the Enter Website or GitHub URL option from the main menu of the addon. A popup will come up asking you to enter in the URL of a Kodi Repository location.

Some basic examples of URLs you can enter include:

    nixgates.github.io – This is an example of a basic repository address, like what you see on all of our guides.
    https://forum.kodi.tv/showthread.php?tid=328558 – This is a link to the Kodi Forums to the Aura skin page. The addon knows to scrape the page for the repository link there.
    https://github.com/opensubtitles/service.subtitles.opensubtitles_by_opensubtitles – This is a link to the zip page on GitHub for the Opensubtitles addon. You can enter in any GitHub zip url to directly install the repository from GitHub without knowing the source.

For more ideas on Kodi Repo URLs, you can check out our best Kodi addons list for the top addons.

 
How to Setup a Kodzi List

Kodzi supports the creation of a list. A list contains multiple Kodi repositories in one single file. The addon reads that file and allows you to quickly install multiple repositories fast.

To create a list, you must create a file in the following format:

    kodzi-title = “Example”

    kodzi-name = “Seren”, url = “nixgates.github.io”
    kodzi-name = “Aura”, url = “https://forum.kodi.tv/showthread.php?tid=328558”
    kodzi-name = “Opensubtitles”, url:”https://github.com/opensubtitles/service.subtitles.opensubtitles_by_opensubtitles”

You start by giving you a file a “kodzi-title” for your list. Then, you create separate “kodzi-name” fields for each URL you want to add to your list.

Once you are done, you need to upload your list file to a URL or GitHub repository, something you can type into Kodi.

In the Kodzi Kodi addon, click the Enter Lists URL option and enter in the URL of the list you created. You can enter in https://mrkodz.github.io/repo/Example.txt as an example to install the three repositories listed above.

 
Kodzi Kodi Tips & Tricks
GitHub Clone (GC) Support

The GithubClone command allows you to clone a Github directory. Normal users shouldn’t need to clone any git, but this feature is included for those that need it.

For example: Take opensubtitles ; https://github.com/opensubtitles/service.subtitles.opensubtitles_by_opensubtitles

You can clone it by typing in the Kodzi (‘Enter Website or Github Url…..’) the following

“gc:opensubtitles/service.subtitles.opensubtitles_by_opensubtitles “

Without the (“) . Kodzi will clone and install the subtitle add-on. (If you look carefully at the git, you can see there’s a zip you can download, so if you enter the whole url, Kodzi will also find the zip).

 
GitHub Tree (GT) Support

Github tree allows you to find and install all the zips in the specific directory you are.

Example: https://github.com/nixgates/nixgates/tree/master/packages/plugin.video.seren (Notice the ‘tree’ in URL)

The Kodzi Github Url for that is: “gt:nixgates/nixgates/packages/plugin.video.seren” (without the [“])

This feature is there so that you can navigate to the zip folder of a Github repository manually without knowing the full URL. When you are building your list, you may prefer to add sources this way verses adding the whole URL.
