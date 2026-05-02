---
title: "How I Turned an Old PC Into a 24/7 Home Media Server on a Tight Budget"
date: 2026-05-01
draft: false
category: "PC Tips"
summary: "That old PC collecting dust in the corner still has plenty of life in it. Here's exactly how I turned mine into a always-on Plex media server — storage, remote access, shared folders and all — without spending much."
---

Most people have an old PC sitting somewhere. Under a desk, in a closet, collecting dust because it felt too slow to use as a daily driver. Before you recycle it or let it gather more dust, hear me out — that machine might be exactly what you need for a home media server.

I set mine up a while back and it's been running 24/7 ever since. Movies, TV shows, music, photos — all of it accessible from any device in the house or anywhere in the world. Here's exactly how I did it and what I'd tell someone starting from scratch.

## What Specs Actually Matter

This is where people overcomplicate it. A Plex media server doesn't need to be powerful — it needs to be adequate. There's a difference.

**What matters:**
- **CPU** — The processor does the heavy lifting when Plex has to transcode media. Transcoding is when Plex converts a video on the fly because the device you're watching on can't play the original format. A decent quad-core processor from the last 10 years handles this fine for one or two streams. An Intel i5 or i7 from the 2012–2018 era is more than enough.
- **RAM** — 8GB is comfortable for a dedicated media server. 4GB works but you'll feel it if the machine is doing anything else at the same time.
- **A fast SSD for the operating system** — You want Windows or Linux running off an SSD so the machine boots fast and runs cleanly. The SSD doesn't need to be big — 120GB or 256GB is plenty for the OS and Plex itself.

**What doesn't matter:**
- A dedicated GPU — not essential, but worth having if you can. If your devices can direct play everything Plex sends them, the GPU sits idle. But the moment Plex starts transcoding — converting files on the fly for different devices or remote connections — a dedicated GPU handles it dramatically better than a CPU alone. Even a budget gaming GPU makes a noticeable difference here. If your server has one, keep it.
- A powerful CPU — if your devices can direct play (which most modern ones can), Plex barely touches the processor at all
- Tons of RAM — this isn't a gaming rig, it's a file server

The old PC you have sitting around is probably fine. Don't let the specs talk you out of using it.

## The Storage Problem — And the Cheap Solution

Here's where most home server guides send you down an expensive rabbit hole. They tell you to build a NAS. A proper NAS with a case, drives, and a NAS operating system costs real money and involves more setup than most people want to deal with.

There's a better way.

A **hard drive docking station** changes the whole equation. You plug it into a USB port on your server PC and it gives you multiple drive bays you can slot regular desktop hard drives into. No enclosure to build, no RAID configuration to wrestle with, no NAS operating system to learn. Just plug in a drive and it shows up like any other storage.

The one I actually use is the [MAIWO 5 Bay Hard Drive Docking Station](https://amzn.to/4tGIt1q). Five bays, USB 3.0 with UASP for fast transfer speeds, supports drives up to 120TB total capacity, and it has an offline clone function built in — meaning you can duplicate one drive to another without even involving the PC. That last feature alone has saved me more than once.

You can start with one drive and add more as your library grows. Large desktop hard drives are cheap. A [Seagate Barracuda 4TB](https://amzn.to/3OPR8j3) gives you room for hundreds of movies and TV seasons. If you're planning a bigger library from the start, the [Seagate Barracuda 8TB](https://amzn.to/4namKwC) is the better long term investment and the price per gigabyte is hard to beat. The docking station pays for itself quickly compared to what a proper NAS setup costs.

## Setting Up the Shared Folders

This is the part that makes the whole setup genuinely useful beyond just Plex.

On the server PC, right-click the folders where your media lives — Movies, TV Shows, Music, whatever — and share them on your local network. On your main desktop or laptop, map those shared folders as network drives. They show up in File Explorer exactly like a local drive.

Now when you download something on your main PC, you can save it directly into the shared folder on the server. Plex picks it up automatically, matches it to the right title, pulls in the artwork and description, and it's in your library within minutes. No copying files, no USB drives, no manual transfers. You download it and it's just there.

This is genuinely one of the most satisfying things about the whole setup once it clicks.

## Remote Access — Watching From Anywhere

Because the server is on 24/7, your Plex library is available anywhere you have internet. Hotel room, someone else's house, your phone on the train — open Plex and your entire library is there.

Remote access through Plex works well on the free tier for basic use, but to get the full experience — streaming outside your home network reliably, downloading content to your phone for offline viewing — you want a [Plex Pass Lifetime](https://www.plex.tv/plex-pass/). You pay once and remote access works forever. For a setup you're going to use every day indefinitely, it's worth it.

## Common Mistakes to Avoid

**Using the server as a daily driver too.** The whole point of a dedicated server is that it's always on and always available. If you're using it as your main PC as well, it's getting shut down, restarted at inconvenient times, and loaded with software that has nothing to do with serving media. Keep it dedicated.

**Skipping the SSD for the OS.** Running Windows off an old hard drive makes the machine slow to boot and sluggish to manage. A cheap SSD for the operating system makes a night and day difference — something like the [Patriot Burst Elite 120GB](https://amzn.to/49hW0UT) is all you need. Remember, this drive is only for Windows and Plex itself — your actual media goes on the hard drives in the docking station. Size does not matter here, just speed.

**Not planning storage properly.** Think about how much content you actually want to store. Movies average 10–20GB each for good quality. A 4TB drive holds around 200–400 movies. Plan ahead so you're not constantly scrambling for space.

**Forgetting about heat and placement.** This machine runs 24/7. Don't put it in a closed cabinet or a tight space with no airflow. Give it room to breathe and make sure it's been cleaned out — a server clogged with dust running around the clock is a recipe for an early death.

**Not setting up a backup.** The docking station's offline clone feature exists for exactly this reason. Clone your main media drive to a backup drive periodically. Hard drives fail. Having a backup means losing a drive is an inconvenience, not a disaster.

## The Running Costs

A reasonably modern desktop PC in idle uses somewhere around 30–80 watts depending on the hardware. Running 24/7 that adds to your electricity bill but it's not dramatic — and sleep mode isn't really an option for a server that needs to be available at any time.

The tradeoff is worth it for most people. A proper NAS device uses less power but costs significantly more upfront. An old PC you already own with a docking station and a couple of hard drives gets you most of the same functionality for a fraction of the cost.

## Why Old Machines Still Have Plenty Left in Them

A PC that felt too slow for daily use in 2024 is still perfectly capable of serving media files. Plex isn't asking it to run Chrome with forty tabs open or handle a video call — it's asking it to read a file off a drive and send it across the network. That's not a demanding task.

The machine that felt retired still has years of useful life as a server. It runs something it's genuinely good at, it stays out of the way, and it earns its keep every single day.

---

> **Adam's Take:** This is one of my favourite setups I've ever put together. The old PC was sitting there doing nothing, the docking station was a fraction of what a NAS would have cost, and now I have a media library available on every screen in the house and anywhere in the world. The shared folder trick is the part people don't talk about enough — having downloads go straight into the Plex library from my main PC without touching anything manually is genuinely satisfying every single time. If you've got an old machine gathering dust, this is what it was made for.
