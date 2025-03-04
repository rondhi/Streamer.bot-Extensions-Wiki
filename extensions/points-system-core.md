---
title: Points System (by VRFlad)
description: The core extension to allow Streamer.bot to have channel points without the need for being a Twitch Affliate.
published: true
date: 2023-03-07T23:49:35.814Z
tags: 
editor: markdown
dateCreated: 2022-10-23T19:36:51.737Z
---

# Tutorial

<br>
<iframe src="https://www.youtube.com/embed/VCnoT7wqNrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; fullscreen" allow fullscreen style="border: none; max-width: 100%; width: 100%; aspect-ratio: 16/9;"></iframe>

Current Import has been updated since the video was recorded.

# Import Code 
```text
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
```

# Installation
In Streamer.bot in select `Import` from the top left.
Copy the `Import Code` and paste it into the `Import String`. 

This setup allows an easy way to have a points system in Streamer.bot without any complicated maintenence and should allow for a one and done setup.


This Import Contains 13 Actions and 9 Commands, note commands are disabled by default

# Configuration

## Points Name

You can use the command `!setName` to set the name of the Points. Example `!setPoints UFO's` will change them to UFO's.

## Timed Action

To automatically give points to your viewers while watching set the `Action` `[Points] - Timed Action` to the `Event` `Present Viewers`.

![points-system-present-viewers.png](/assets/points-system/images/points-system-present-viewers.png)

## Raid

To award points to users when they raidyou set the `Action` `[Points] - Add Points for Raid` to the `Event` `Raid`

![points-system-raid.png](/assets/points-system/images/points-system-raid.png)


## Moderator and/or Broadcaster Only Commands

As Previously Mentioned Commands are disabled by default, you will need to ensure the following commands also have broadcaster/mod Permssions.

```
!addPoints
!setPoints
!pointsccreset
!pointsccsetname
!setName
```

## Community Challenge Usage (Optional)

To use the Points System optional Community Challenge the following commands should be created:

## Moderator and/or Broadcaster Only Commands (Community Challenge)

Using `!pointsccsetname This month's Community Challenge will benefit UNICEF!` will set your Community Challenge Description to `This month's Community Challenge will benefit UNICEF!`


When using `!pointssetcctotal 10000` will set your Community Challenge Goal to 10,000 points.

Using `!pointsccreset` will reset your Community Challenge and clear out the all the points contributed!




## User Commands (Community Challenge)


When a user uses `!pointscc` in chat it will return `The` `pointsname` `challenge -` `communitychallengename` `is at` `communitychallengecurrpoints` `out of` `communitychallengetotalpoints.` if there is a Community Challenge active.  Otherwise, it will return `There is no current` `pointsname` `community challenge.`



When a user uses `!contribute 100` in chat it will add 100 points to the Community Challenge and deduct the points from the user's points total.



# Contributors

 - [VRFlad](https://www.twitch.tv/VRFlad){.twitch}
 {.contributors}
