---
title: "How to Save Knowledge Sessions Locally"
subtitle: "Don't trust you'll get to all the content soon enough?  Me either."
summary: "Here's a way to save off the video content when ServiceNow decides to drop the data."
date: 2020-05-14T10:51:44-05:00
---

So I was in the "Automate ServiceNow CI/CD" lab and the question came up, "How long will this session be online for me to view?".  I'd link to it but the links are terrible because they change, hence this post.

If you don't trust you will get to the lab/video soon, I'd encourage you to save the video locally so you KNOW you'll have it to watch later.

I can hear you now, Jace, how can you do that?  Well it seems the K19 and K20 both used this Brightcove video delivery system.  Brightcove videos are not the simpliest to download but, you can save a video in about 5 clicks.

1.  Right click the video being presented, open "Player Information"
2.  Copy the "Video ID" into this string replacing YourVideoID `http://players.brightcove.net/5703385908001/zKNjJ2k2DM_default/index.html?videoId=YourVideoID`
  - <input value="http://players.brightcove.net/5703385908001/zKNjJ2k2DM_default/index.html?videoId=YourVideoID" style="width: 100%;font-size: 10px;"/>
3.  Take that string and paste it into [bitdownloader.com](https://bitdownloader.com) and click the "Download".
4.  Now at the bottom is a list of videos with resolutions, Right click the video download button at the bottom, and click Save as, give it an apt name and you're set.
