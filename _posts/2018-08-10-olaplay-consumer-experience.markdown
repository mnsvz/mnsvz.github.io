---
layout: article
title:  "OlaPlay Consumer Experience"
date:   2015-08-10 13:57:09
headline: "Redesigning in-cab entertainment for OlaPlay"
co: "Ola"
tags:
- ui
- interaction
categories:
- published
---

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_olaplay_cover.jpg" />
</figure>


<!--more-->



## Introduction

Ola Play is the world’s most advanced connected car platform. It brings advanced car controls, choice of personalized content, and a fully connected interactive experience to the user. Cars are equipped with a range of infotainment options and enhanced driver assistance.

Users can tune into their favourite radio shows, catch up on sitcoms, enjoy movies and much more. Going home, to work, or maybe heading to the airport, users can enjoy comfortable rides with entertainment on-the-go.

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_olaplay_media.jpg" />
</figure>

---

## Context & Research

As of 2017, the consumer experience was limited to watching videos and listening to music during the ride. We planned to scale this beyond music, movies into gaming, localised content and commerce. Some of the problems we identified and plan to solve for were as follows-

<strong>It was very hard for users to discover new and personalised content - </strong>
To help with the launch, the consumer tablet always showcased content partner apps on the home screen. This was a thoughtful measure to bring about familiarity in content to this new "in-car experience" for Indian consumers. However, as content and number of Play rides scaled, this proved to be a bottleneck for new content discovery by users. Most users would stick to one or two channels that they recognized which lead to a very narrow spread in engagement.

<strong>The V1 interface was not scalable for non-media use cases, like commerce and gaming - </strong>
The Version 1 of consumer tablet experience was designed for consuming music and video during a cab ride and the navigation was failing to scale beyond entertainment and cater to newer product segments such as local commerce and in-car gaming.

<strong>Low scores on perceived safety from users - </strong>
Repeated user surveys and interviews suggested low scores on perceived safety in Ola cabs. As a part of the overall organisational effort, we had to enable quick and easy access to emergency controls in OlaPlay cabs as well. 

<strong>Low scores on brand awareness+recall for Ola Play - </strong>
Numerous user interviews with the larger share of Ola's customers revealed that many people were not aware of this category of cabs equipped with entertainment consoles. Our research team also deduced that the interface did not have many cues that strengthened OlaPlay's brand. This made users slightly apathetic towards repeated booking of OlaPlay cabs.


<strong>No efforts towards personalising the ride for the user - </strong>
User research also indicated that there was a gap in the experience that when bridged could make each OlaPlay ride magical and a personal one.

<strong>Searching for content was hard on an in-car setup - </strong>
We conducted usability tests by accompanying some users on a cab ride and quickly found out that simple tasks like searching, typing on a tablet was taxing and prone to errors while sitting on the back-seat of a car.

During the last 12 months, I led a team of 2 product designers and 2 UX researchers on the redesign of the in-cab consumer experience.


---
## Design & Prototyping

First order of business for the design team was to empathise and understand the situations and moods of daily commuters on Ola. They were often stuck in a cab for hours, either on daily commutes between home <> office or those long and boring rides to the airport.

The cab rides would often be subjected to harsh traffic noise and bumpy Indian roads, making it even harder for users to interact on a touch device. We had to internalise our learnings on the discomfort of interacting with a tablet from the backseat of a car, which is 2 feet away. 

###So what constitutes a great in-cab experience at 2 feet? 

Entertainment UI should offer effortless navigation and control, keeping the user's focus on content. At 2 feet, this was twice as important. We wanted users to sit back and enjoy without having to lean front and touch often to make decisions. We had to study and take cues from the in-home TV experience for android and apple TVs and retrofit them in the context of a moving cab.

In brief, the redesign involves and advocates for ‘design for distance’ by minimizing text inputs and having a content first approach.

The redesigned UI allows zero typing by the user. Most common tasks like searching and typing queries would now be handled by an omnipresent voice search assistant. Ola partnered with Microsoft and the engineering team worked on deep integration of Cortana services, enabling users to perform system-wide voice searches easily.



<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_olaplay_2feet.jpg" />
</figure>

---

Some of them were already doing business on Facebook and Whatsapp. They would display products/services and close deals via Cash or NEFT bank transfers. This put forth a strong use-case for an Android app that enables merchants to conduct day-to-day commerce on their phones powered by Instamojo.

The app had to be good at 2 things. 
Phase 1) Enable our existing merchants to conduct most of their commerce on their phones, on the go.
Phase 2) Act as a acquisition channel of the next billion merchants, who have only known "the mobile way" of doing business.

Invoicing, transactions and tax related workflows are complex and are best designed on a web/desktop interface. The team decided to offer features that enabled merchants to do basic but frequent tasks like-
1) Creating & Sharing payment/product links
2) View the latest sales figures in realtime with filters
3) Enable merchant sign-ups on the app, leading to new user acquisitions

---
## Sketch & Ideation

The biggest constraint was creating something that would be within the scope of a mobile app. I started by defining the most important information to communicate. My inner monologue went something like this — “What is the biggest value provided by this app — the ability to see each new sale in realtime. Do we want to show a sales breakdown by Day, Week, Month, and All Time? What value is added between Week and Month? Do we want to provide a breakdown of sales by product or should that segmentation be for a later release?”

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/olaplay_music_player.gif" />
</figure>

---

I then started sketching out the flow and defining scope with decisions such as letting users log in, but not sign up (for the v1 MVP) since this was more of a tool for existing users rather than an acquisition channel to reach new users. We also removed a few things from the scope such as photos of products and any detailed /information/interaction with the sales info, so we could make sure we would be able to ship this quickly.

One thing I kept in mind was, putting the emphasis on the customer rather than the purchase. Out in the field, merchants would talk and interact with people and close a deal, merchants remember their customers very well and track stuff mentally using their names, it’s more important to highlight that there are people behind these transactions. These merchants have chosen to use Intamojo because they want a direct relationship with their audience, so we should help them feel this relationship.

---
## Design & Prototyping

We finalised the flow of the app and the main dashboard contents during brainstorming and white-boarding sessions. The dashboard is designed to be the go-to place for merchants to track their sales in the last day/week/months and hence that’s the primary focus on the dashboard. Along with the sales numbers, we also provided numbers that indicate growth/dip in business compared to the previous day/week/month.  

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/olaplay_volume.gif" />
</figure>

---

Another objective of the andriod app was to enable merchants to create and share payment links and products directly from the app. Since we saw patterns in sharing via Whatsapp, Email and Facebook, we made it easy for merchants to share their links/products on these platforms. Prior to this, merchants would copy-paste links into mails and whatsapp manually.

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_dbxmobile_cover.jpg" />
</figure>

---

While the team got onto making the android app, I carved out time to make details within the app, animations,empty states and prototypes to help convey some interaction ideas and also to bring delight to customers via small moments and micro-interactions.



<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_dbxmobile_cover.jpg" />
</figure>

---

## Results & Future Track

We ended up shipping the app in 6 weeks and our customers loved it. We kept seeing more and more existing merchants using the android app on a daily basis. We also got requests from our community for an iOS version as well.

---

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_dbxmobile_cover.jpg" />
</figure>

---

This is beyond the scope of this project, but in the future we could help creators manage their capital & shipments. While working on these designs, I realized how difficult it can be for merchants with larger audiences to manage their capital & shipments. SMBs usually struggle with liquidity on a daily/weekly basis that can aid their procurement or fullfillment of the orders. Instamojo has later taken this business challenge up and launched mojo-express and mojo-capital.

### This redesign was sadly not prioritized within the company during my tenure.
