---
layout: post
title:  "Spotify has a problem"
date:   2022-08-26 13:05:28 +0200
categories: spotify
---

I use Spotify a lot. It helps me to concentrate on my work tasks (I have a playlist with carefully selected [trip-hop][trip-hop-playlist] tracks for that), to make my cooking less boring and, finally, to relax after a long day. 

Every week Spotify creates two personalized playlists for me, namely **Discover Weekly** and **Release Radar**, with a selection of tracks from the artist I like or might like based on my music taste. Overall these playlists are great, especially the Release Radar one, since it lists all the new tracks from the artists I follow. But sometimes this very same playlist contains weird tracks that sound nothing like what I usually listen to. This comes as a surprise and I can't help wondering what a heck was that when switching to the next track. Just to give you some context here is what I'm talking about:

<!-- ![A screenshot showing a weird track in Spotify playlist](/assets/2022/08/revvv.png 'A shitty track suggestion') -->

{% include image.html file="/assets/2022/08/track.png" description="Revvv by Veeh K, Sonya Belousova and Cleo Sol." %}

## Who the fuck is Veeh K?

{% include image.html file="/assets/2022/08/veehk.png" description="Even with 7 followers you can be a verified artist." %}

Let's investigate. **Veeh K**, if it's his real name, is new in town but he is already a verified artist. He has produced 5 songs in total but managed to collaborate with several known artists. All of the albums in his discography are singles. 
All of his 7 listeners come from US, Spain and Germany. There are also 3 followers that are hidden from public.
Overall seems like a legit artist account.

{% include image.html file="/assets/2022/08/stats.png" description="Are these 7 monthly listeners even real?" %}

## The hack

Veeh is a smart guy. He uploads some shitty tricks of his and then uses a special hack to promote those on Spotify. In order to get higher listener count for each of his tracks he specifies several known artists names as if they collaborated with him. For instance, the credits of his *Revvv* track pictured above clearly state both Sonya Belousova (a producer of "Toss a coin to your Witcher") and Cleo Sol (fantastic RnB singer) as performers. I bet none of them have ever heard of Veeh K. But that does not concern Veeh. He gains massive play count by parasitizing on fan bases of real and popular artists. In this case, this week all fans of Sonya Belousova and Cleo Sol were suggested Revvv song as part of their weekly Release Radar playlist. They listened to this shitty song, thought "what a fuck?", skipped to the next song and yet again realized that Spotify's music suggestion algorithms are not perfect. Veeh K meanwhile got millions of song plays and will probably cash out before he gets flagged and blocked by Spotify. 

## The problem & possible solution

The problem of Spotify is that there is no built-in check whether the song was indeed produced by the stated artists. Anyone can upload their track and claim Kanye West collaborated on it. But did he, really?

One way to overcome this problem is to request authorization from each stated artist before the song becomes available. Similar to the way we review pull request in software development. While it might be overwhelming for an artist to distinguish between real collaborators and fake ones, a good UI design and some ML-prediction might help to ease the process. 

Bu for now, I will keep on getting weird tracks in my Spotify weekly. 

[trip-hop-playlist]: https://open.spotify.com/playlist/0Y2LEBRex7KvbeuoEtyqSW?si=5ec169f4de1d44cf