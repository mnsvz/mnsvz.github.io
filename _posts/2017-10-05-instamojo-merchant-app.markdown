---
layout: article
title:  "Instamojo Merchant App"
date:   2016-05-30 13:57:09
headline: "Instamojo Merchant App"
co: "Instamojo"
tags:
- ui
- interaction
categories:
- published
---


<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_cover.jpg" />
</figure>

<!--more-->
---

## Introduction

Instamojo provides free payment gateway in India. Trusted by 5,00,000+ Indian Businesses, 100% Secure, No setup cost, No maintenance cost. Instamojo offers some great tools that can not only help you manage your business efficiently but also help you grow your business.



## Problems with Instamojo web


Merchants couldn’t see their new sales on mobile, so they had no way of tracking their realtime earnings on the go. At Instamojo, we had conducted user research and surveys across tier-1 & tier-2 cities in India. We found 80% of the SMB merchants had a smartphone with 3G connectivity, and only around 15% of them had laptops/desktops. 

This put forth a strong use-case for an Android app that enables merchants to conduct day-to-day commerce on their phones. Up until this point, there was no android app for merchants. They were only notified of new sales through email, like the one below.


<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_email.jpg" />
</figure>

---

If the merchant wanted to see the total amount they’ve now made on Instamojo, they would have to log in to the site and navigate to their Sales dashboard. The information on new sales and total sales is completely separate, and there are additional steps involved if you want that data.

---

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_webapp.jpg" />
</figure>

---

With the emphasis on total sales rather than new sales, it can be tough for merchants to get a sense of new sales coming in. From a business standpoint, we should make it ridiculously easy for merchants to see how Instamojo is helping them every single day. 

I was teamed up with our amazing Product Head, Dalan and Developer, Vedhvyas to get started on this project.

---
## Research and Context

The need for the merchant app was driven mostly by continuous customer emails and tweets asking for a mobile solution to track sales and share products/links on the go.

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_tweets.jpg" />
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
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_sketching.jpg" />
</figure>

---

I then started sketching out the flow and defining scope with decisions such as letting users log in, but not sign up (for the v1 MVP) since this was more of a tool for existing users rather than an acquisition channel to reach new users. We also removed a few things from the scope such as photos of products and any detailed /information/interaction with the sales info, so we could make sure we would be able to ship this quickly.

One thing I kept in mind was, putting the emphasis on the customer rather than the purchase. Out in the field, merchants would talk and interact with people and close a deal, merchants remember their customers very well and track stuff mentally using their names, it’s more important to highlight that there are people behind these transactions. These merchants have chosen to use Intamojo because they want a direct relationship with their audience, so we should help them feel this relationship.

---
## Design & Prototyping

We finalised the flow of the app and the main dashboard contents during brainstorming and white-boarding sessions. The dashboard is designed to be the go-to place for merchants to track their sales in the last day/week/months and hence that’s the primary focus on the dashboard. Along with the sales numbers, we also provided numbers that indicate growth/dip in business compared to the previous day/week/month.  

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_sales.jpg" />
</figure>

---

Another objective of the andriod app was to enable merchants to create and share payment links and products directly from the app. Since we saw patterns in sharing via Whatsapp, Email and Facebook, we made it easy for merchants to share their links/products on these platforms. Prior to this, merchants would copy-paste links into mails and whatsapp manually.

---

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_links.jpg" />
</figure>

---

While the team got onto making the android app, I carved out time to make details within the app, animations,empty states and prototypes to help convey some interaction ideas and also to bring delight to customers via small moments and micro-interactions.


---

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_load.gif" />
</figure>

---

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_fab.gif" />
</figure>

---


## Results & Future Track

We ended up shipping the app in 6 weeks and our customers loved it. We kept seeing more and more existing merchants using the android app on a daily basis. We also got requests from our community for an iOS version as well.

---

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_future.jpg" />
</figure>

---

This is beyond the scope of this project, but in the future we could help creators manage their capital & shipments. While working on these designs, I realized how difficult it can be for merchants with larger audiences to manage their capital & shipments. SMBs usually struggle with liquidity on a daily/weekly basis that can aid their procurement or fullfillment of the orders. Instamojo has later taken this business challenge up and launched mojo-express and mojo-capital.

### Track your sales wherever you go. <a href="https://play.google.com/store/apps/details?id=com.instamojo.app&hl=en_IN">Download Intamojo from the Play Store</a>.
