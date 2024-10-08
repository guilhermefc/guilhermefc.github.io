---
layout: post
title: Creating a Google Podcasts Clone
lang: en
image: podcasts-graveyard.webp
lang-ref: gpodcasts_clone
---

##### **TL;DR;**

- \- Behind the scenes of creating a podcast player app inspired by Google
  Podcasts.
- \- Results achieved 3 months after the alpha launch.

<br /> Who hasn't felt frustrated using a discontinued service? That was the
excuse I needed to create an app that could come close to the experience Google
Podcasts offered. Even though creating yet another podcast player app in 2024,
with so many available options, might seem like a terrible idea.

<br />
Minimalist apps attract me; I think that's why the end of that app bothered me
so much. I don't like cluttered experiences, being stuck between too many
features and choices. With that in mind, the idea was clear: to bring the
apparent simplicity of the defunct app and add an extra layer of minimalism,
targeting users who want to listen to what they love with just one click,
without having to go through a dozen choices to get to their favorite content.
I'm talking about Spotify, YouTube, Netflix, and so many others that bundle so
many services to keep you hooked that, sometimes, without even realizing it, we
end up spending minutes or even hours just browsing the menu of options.

<br />
To get started, I went with the stack that made the most sense with the
technologies I know. I used Flutter to develop both the Android and iOS apps.
For the backend, I chose to build the functionalities using Supabase, an
alternative to Firebase that offers various backend services as a platform. This
allowed me to quickly build the necessary screens and CRUDs.

<br /> One challenge along the way was figuring out where to pull the podcast
database from. Let me try to explain simply how this works: to have a public
podcast available on the internet, all you need to do is upload an audio file
with the program and add the metadata of that program into an XML file. That's
enough for some podcast indexer service to find your program and display it in
public podcast apps. There are exceptions to this flow, like with Spotify and
YouTube, but the origin of podcasts follows the format I mentioned, and this
prevents podcasts from becoming a monopoly like YouTube and similar apps did
with the video segment.

<br /> That's why I must thank the team behind Podcast Index. This independent
project is dedicated to protecting and preserving the podcast ecosystem,
ensuring that content creators have a free and accessible space to share their
voices. Thanks to them, I was able to access a robust database with millions of
podcasts, which was essential for the app's launch. Without them, creating a
podcast indexer from scratch, given the time I had available, would have been
nearly impossible, and the app certainly wouldn't have reached the same quality
and scope.

<br /> This is how I managed to turn the frustration of losing a beloved service
into an opportunity. Minimal Podcast isn't just a clone of Google Podcasts; it's
a response to the dissatisfaction of seeing cool products disappear.

<br /> Of course, comparing an app developed in a month by a single person to an
app that had billions of users and was maintained by one of the largest tech
companies on the planet would be incredibly arrogant on my part. So, let me be
clear: I only used its appearance as inspiration, and there are still many
improvements needed for the recommendation engine and other features... but
little by little, we're getting there.

<br /> In the first month after launch, Minimal reached 2,000 downloads on the
Play Store and App Store, with very little marketing effort. Marketing is a huge
challenge for me, but this shows that I'm not the only one who missed a
minimalist and straightforward podcast experience.

<br /> But this is just the beginning. I'll share, from time to time, the pains
and triumphs I'll face as I continue developing the app. And here's a spoiler:
creating and maintaining a user acquisition channel and monetizing those users
so the finances balance out is my next big challenge. Slowly but surely, we're
getting there.
