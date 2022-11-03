---
layout: post
title: HOME ALONE
date: 2021-05-02
description: Projection, mapped to wooden frame 1.5x1.5m; 2021. # Add post description (optional)
img: figs_HomeAlone01.JPG # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [machine-learning, video, projection] # add tag
---
<p align="center">
Projection, mapped with wooden frame ~1.5x1.5m; 2021.<br><br>
"We are alone, with no excuses. That's the idea I shall try to convey when<br>
I say that [we are] condemned to be free."<br>
- Jean-Paul Sartre<br><br>
<iframe width="670" height="377" src="https://www.youtube.com/embed/O27S71gmMeM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<img src="{{site.baseurl}}/assets/img/proj_iwasalwaysthere-10.jpg">
</p>

For communities of folks of Hong Kong, home serves as a different space full of their individual stories. It can be a luxurious interior for social connection, or a crammed space for a quarantine, or a work place for both caretakers and work-from-homers. The diverse spectra of lives in Hong Kong can be experienced as their narratives in the place they spend the most time of their lives in, their homes. Home Alone is a narrative landscape of the interior spaces of Hong Kong, from crammed spaces of domestic workers to high rise mansions of urban yuppies. It evolves from the serene bedroom scene to the stuffy bathroom to the window-filled high rise to the compact guestroom for its domestic worker populace to eventually the abandoned houses of Yim Tin Tsai, where we find ourselves finally left alone only with their previous narratives in the form of broken bottles, ragged dolls, and ancestral photos. Finally, we are home alone in Hong Kong.

Home Alone is a StyleGANS machine-learning-based traversal of latent spaces of the interiors of Hong Kong homes, with the objects and features of the room serving as narrative devices. Home Alone was exhibited as part of I'm Always Here at [Osage Gallery Hong Kong][show]. Home Alone was shown at the Art and Tech Exhibition at [The Ammerman Connecticut Biennial][ammerman].

[show]: {{site.baseurl}}/assets/img/ImAlwaysHere_Pamphlet_RAYLC_crop.pdf
[ammerman]:
http://artsandtechsymposium.digital.conncoll.edu/participants/

<p align="center">
<img src="{{site.baseurl}}/assets/img/proj_iwasalwaysthere-24.jpg">
<img src="{{site.baseurl}}/assets/img/figs_homealoneosage01.gif">
</p>

The inspiration for the work comes from my arrival to Hong Kong in December 2020 at the height of quarantine. From my highrise hotel in LKF I got up every morning with the rise of the sun to find that at 6:15am everyday, a mother strolls her baby outside on a nearby rooftop. It became a habit for me everyday as the time stopped during quarantine to look out every morning and find the mom and child repeating the same ritual, before it finally dawned on me that of course, they were also in quarantine. That's why she gets up early so that no one is at the rooftop, and also so that she doesn't have to take the baby outside for the sun per the quarantine restriction. I began to think about how different everyone's quarantine in Hong Kong is, from a beautiful highrise mansion to a domestic worker's flat, to a cheap hotel. To see all these views of interiors during a collective quarantine, we took photos as well as online photos of HK interior spaces to train StyleGANS2, in order to traverse the states of possible spaces and visualize the possible experiences of HK residents.

Upon completion of this phase, however, I saw that while we showed HKers experience, we did not show their mental states. Everywhere I ran into people who wanted to leave, contrasting with my own attitude of freshly arriving in Hong Kong, expecting possibilities of change and excitement. How can I also show that feeling in the spaces they occupy? Unlike classic ML methods which usually take datasets that have low variability, we decided to bring in a completely different set of data of abandoned homes in HK, including those of Hakka villages and public buildings (theatres, schools, etc) that have since been abandoned. We found these by searching through facebook groups on urban exploration (urbex) and locating them ourselves, then taking photos of these spaces when we arrive. We had expected the model to traverse sequentially from locations of higher residential organization to more and more disorganized places as seen in the abandoned locales, but interestingly the algorithmic traversal would sample both interiors and abandoned locales equally, traversing between them in due time multiple times per loop. It's as if ML is telling us that averaged over all these experiences, HKs may abandon their homes, but they always really come back, in heart or in reality, for the traversal eventually goes from abandoned back to interior in due time.

The newly formed model with the photos of abandoned places then gives a narrative framing for the situation of HK: people who want to leave due to political pressures, and then also people whose spirit eventually returns, because at the end, people never really leave their homes, they always go home. Hence in my naive quarantine view of that rooftop of a mother strolling her child, I found a glimpse of HK through the way spaces are represented and summarized by ML, but I also through my naivete, saw a place that is repeated abandoned and returned to by its inhabitants, a place that eventually returned to, home alone.

<p align="center">
<img src="{{site.baseurl}}/assets/img/figs_HomeAlone01.gif">
<img src="{{site.baseurl}}/assets/img/figs_HomeAlone02.jpg">
</p>

The initial install used a wooden frame to contain the vision of alternative reality presented by the machine. However we felt that this did not contribute to the story of interpreting machines and how we look at the process of looking at machines and their dreams of the spatial realities. Thus for Osage Gallery we lifted the projector higher, used a higher resolution output, and put a frame between the projector and the output projection. This purposely puts a distance between the output vision generated by the machine and the way of producing that image, emphasizing the process of looking at an ML artwork as essentially through a filtered window of reality. As we look through that window, we step into a world where parallel visions are hinted at, where we can see each others' alternative worlds as opposed to only our own, and where the projector becomes a catalyst in that perception.

The installation requires a 2000-3000 lumens or more (can be short throw) projector showing a 1024x1024 video files that loops consistently every two and a half minutes. The position of the wooden frame is dependent on the particular gallery, but generally the image should shine through the inner sides of the frame without illuminating the exterior of the frame. When the frame is moved (by human visitors, for example), it creates a curtain-like feeling on the projected output, much as the shadows modifies the perception of reality in Plato's cave. The projected surface on the wall should be about 2.5x2.5 meters, and the frame should be 0.8x0.8 meters, but galleries who don't have the capability for that type of spatial output can also mount a size of their choice or put the frame on the wall. To get the drifting curtain effect, the frame should be hanging on lightweight rope on two points of contact. Finally we added music generated using GANSynth which transforms the timbre of the sound on a ML-generated accompaniment to my own improvised jazz piano playing which loops to the same time frame. This can be played with the video if desired, and can be provided by the artist upon request.

<p align="center">
<img src="{{site.baseurl}}/assets/img/proj_iwasalwaysthere-25.jpg">
<img src="{{site.baseurl}}/assets/img/proj_iwasalwaysthere-54.jpg">
</p>
