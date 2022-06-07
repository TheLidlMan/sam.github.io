---
title: TITLE
date: 2022-01-01 00:00:01 +0800
---

# Pi-Hole Adlist

The Internet is full of unsavoury content: advertisers wanting to sell you stuff you don’t need, trackers extracting and selling your data as if it were oil, and malicious content vying to hijack your favourite device. This collection hopes to help you minimise these issues, and to maintain a more enjoyable online presence, using the wonderful, free and open source utility known as Pi-hole.

Using the following method I will help you add all the ad and tracker lists you may need to complete your Pi-hole setup and secure you home network.
#
## Step 1:
![](https://www.sammatthews.co.uk/wp-content/uploads/2022/02/image-22.png)
Open the dropdown menu ‘Group Management’ in the sidebar

![](https://www.sammatthews.co.uk/wp-content/uploads/2022/02/image-23.png)
Now select ‘Adlists’ from the dropdown menu

![](https://www.sammatthews.co.uk/wp-content/uploads/2022/02/image-22.png))
Now you should see this screen
#
## Step 2:
Now you can open either of the following links

Full (might cause issues and more fiddling) – Full-on-Adlist.txt

From firebog.net, edited
Lite (tried and tested unlikely to cause issues) – Lite-List.txt

From firebog.net, edited
#
## Step 3:
Now select all the links there using CTRL + A, then copying it with CTRL + C, then paste it in into the Address section on the Pi-hole web interface that we opened up just above. Then for the comment you can just put ‘Firebog Full on Adlist’ or ‘Lite List’ depending on which one you chose
#
## Step 4:
Now to make sure that the services you use on a daily basis still work I would highly recommend you add the following URLs to your whitelist which can be found under the whitelist tab on the side bar, open it up and follow onto the next step

#
## Step 5:
Open this Commonly Whitelisted Domains and copy and paste the following domains that apply to your setup and which devices or services which you use.
#
# End Note
I hope this helped you in building your ultimate Pi-hole setup