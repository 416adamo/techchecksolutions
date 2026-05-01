---
title: "Already Running a Plex Server? You Don't Need Google Photos Anymore"
date: 2026-05-01
draft: false
category: "PC Tips"
summary: "Google Photos keeps shrinking your free storage and your private memories are sitting on someone else's server. If you're already running Plex, you're closer to fixing both of those problems than you think."
---

Google Photos is genuinely great software. Nobody's arguing that. But at some point you hit the storage limit, Google holds your hand out for a monthly payment, and you realize that every photo you've ever taken is sitting on a Google server somewhere. That part sits a little differently depending on how you feel about it.

If you're already running a Plex server at home, you have everything you need to replace Google Photos entirely. It takes about an hour to set up, costs nothing, and once it's running you never think about it again.

Here's exactly how I have mine set up.

## The Problem With Google Photos

It's not that Google Photos is bad. It's that you don't own any of it. Your photos live on Google's infrastructure, subject to Google's terms, Google's pricing, and whatever Google decides to do next. Remember when they changed the storage policy and suddenly everyone's free unlimited storage wasn't unlimited anymore? That wasn't a surprise — it was always their call to make.

There's also the privacy angle. Every photo you take automatically uploads to a company that makes its money from data. Most people shrug at this. Some people don't. Either way, there's an alternative.

## The Shoebox Analogy

Think about how people used to store photos before smartphones. Printed copies in a shoebox under the bed. Nobody could access them but you. Nobody could change the rules on you. They were just yours.

Google Photos is like handing your shoebox to a very organised friend who promises to keep it safe, sort everything by date, and let you look through it whenever you want — as long as you keep paying them and they don't change their mind.

What we're building here is your own organised shoebox. Still sorted, still searchable, still accessible from your phone anywhere in the world — but sitting on your computer at home, not someone else's server.

## What You Need

- A computer running Plex (which you already have)
- Resilio Sync — free app, available on Windows, Mac, Linux, iOS and Android
- The Plex Photos app on your phone
- About an hour

That's it. No subscriptions, no new hardware, nothing to buy.

## How It Works

**Resilio Sync** is the key piece here. It's a sync app that connects folders across devices directly — no cloud middleman. Whatever goes into a watched folder on your phone shows up in the corresponding folder on your PC automatically, over Wi-Fi or mobile data.

I set up three synced folders: my camera roll, my WhatsApp images, and my message photos. The moment a new photo hits any of those folders on my phone, it syncs straight to my Plex PC. I also have it syncing to my main desktop as a second backup — so every photo I take ends up in two places on my home network without me doing anything.

**Plex** then reads the folder where those photos land and organises them into a proper photo library — sorted by date, searchable, with a clean interface. Pull up the Plex Photos app on your phone and it looks and feels like a proper photo gallery. Your whole collection, available anywhere you have internet.

## Setting It Up

**Step 1 — Install Resilio Sync**

Download Resilio Sync on your PC from their website and install it. Then install the Resilio Sync app on your phone from the App Store or Google Play.

Create a folder on your Plex PC where you want your phone photos to land — something like `C:\PlexMedia\PhonePhotos\Camera`. In Resilio Sync on your PC, add that folder and it'll give you a link or key to connect it.

On your phone, open Resilio Sync, tap the plus button, and paste in that key. Point it at your phone's camera folder. From now on, new photos sync automatically.

Repeat this for any other folders you want — WhatsApp images, screenshots, whatever makes sense for you.

**Step 2 — Add the folder to Plex**

In Plex, go to your libraries and add a new **Photos** library. Point it at the folder where your synced photos are landing. Plex will scan everything and build your library.

One tip here: keep your camera photos in their own folder separate from WhatsApp and message images. Plex handles a clean camera roll beautifully. A mix of memes, screenshots and WhatsApp stickers alongside your actual photos can make the library feel messy.

**Step 3 — Install Plex Photos on your phone**

Download the Plex Photos app — it's separate from the main Plex app and built specifically for this. Sign into your Plex account and your photo library shows up exactly like Google Photos. Scroll by date, search, share — all of it works.

## The Dual Backup You're Getting for Free

Here's the part that doesn't get talked about enough. Because I have Resilio Sync pushing to two machines — my Plex PC and my main desktop — every photo I take gets backed up to two separate physical locations automatically.

Google Photos is one location. One company. One decision away from changing the terms.

This setup gives you two physical copies on hardware you own, plus whatever's still on your phone. That's genuinely better backup than most people have.

## What About the [Plex Pass](https://www.plex.tv/plex-pass/)?

The photo library features in Plex work on the free tier, but remote access — actually viewing your photos from outside your home network — requires a Plex Pass. Which means if you want this setup to truly replace Google Photos and work anywhere in the world, you need it. That said, the [Plex Pass Lifetime](https://www.plex.tv/plex-pass/) is a one time purchase. No monthly fee, no annual renewal, no surprises. You pay once and remote access is yours forever. For something you're going to use every day, that's a pretty easy decision.

---

> **Adam's Take:** I've been running this setup for a while now and I genuinely don't miss Google Photos. My photos are on my hardware, backed up twice, accessible from my phone anywhere in the world. The setup took me an afternoon and I haven't touched it since — it just runs. If you're already hosting Plex you're doing most of the work already, Resilio Sync is the missing piece that ties it all together. The only thing I'd say is keep your camera folder clean and separate from WhatsApp images in Plex — it keeps the library looking the way you actually want it to.
