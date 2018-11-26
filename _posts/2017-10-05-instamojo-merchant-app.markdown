---
layout: article
title:  "Instamojo Merchant App"
date:   2017-05-30 13:57:09
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

## Running a business, on the go!

Instamojo provides free payment gateway in India. Trusted by 5,00,000+ Indian Businesses, 100% Secure, No setup cost, No maintenance cost. Instamojo offers some great tools that can not only help you manage your business efficiently but also help you grow your business.

Since launch in 2012, Instamojo was primarily a web product, offering payment related features to SMB owners with internet access. However, by mid 2016-17 the story of internet access in India was much different. Thanks to the insane sales of reliance JIO connections and availability of cheap and good android phones, internet was suddenly everywhere. Everyone owned a smartphone, and interesting new businesses sprawled around on facebook pages and whatsapp groups.

At Instamojo, we had conducted user research and surveys across tier-1 & tier-2 cities in India. We found 80% of the SMB merchants had a smartphone with 3G connectivity, and only around 15% of them had laptops/desktops. 
We also received a lot of requests from existing Instamojo merchants that they couldn’t see their new sales on mobile, so they had no way of tracking their realtime earnings on the go. 

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

I was teamed up with an amazing Product Head, Dalan and Developer, Vedhavyas to design and ship an android app for merchants.

---
## Research and Context

The need for the merchant app was driven mostly by continuous customer emails and tweets asking for a mobile solution to track sales and share products/links on the go.

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_tweets.jpg" />
</figure>

---

Some of them were already doing business on Facebook and Whatsapp. They would display products/services and close deals via Cash or NEFT bank transfers. We wanted to give merchants the best tool, through an Android app that enables them to conduct day-to-day commerce on their phones powered by Instamojo.

The team brainstormed on many ideas and we were able to reduce the scope by phasing releases and hence ship faster. The goals were as follows -
1. Phase 1 - Enable our existing merchants to conduct most of their commerce on their phones, on the go.
2. Phase 2 - Act as an acquisition channel of the next billion merchants, who have only known "the mobile way" of doing business.

Upon talking to the customers about ground realities of invoicing, transactions and tax related workflows, the team decided that these are best designed on a web/desktop interface. Instead we focussed on offering great experiences that enabled merchants to do basic but frequent tasks like-
1. Creating & Sharing payment/product links
2. View the latest sales figures in realtime with filters
3. Enable merchant sign-ups on the app, leading to new user acquisitions

---
## Sketch & Ideation

The biggest challenge was to make the above mentioned tasks easy on a smartphone. The app had to be designed for clarity and real time information of the business/sales. I started by defining the most important information to communicate. My inner monologue went something like this — “What is the biggest value provided by this app — the ability to see each new sale in realtime. Do we want to show a sales breakdown by Day, Week, Month, and All Time? What value is added between Week and Month? Do we want to provide a breakdown of sales by product or should that segmentation be for a later release?”

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_sketching.jpg" />
</figure>

---

I started sketching out various dashboards with different sets of information ranging from daily sales, to amount of transactions and support tickets that were open. We'd got overwhelming feedback in the interviews that merchants were very eager to know the sales in real time. Often times, these SMB owners were in meetings or on the move and this app would help them be on top of their business.

One thing I kept in mind was, putting the emphasis on the customer rather than the purchase. Out in the field, merchants would talk and interact with people and close a deal, merchants remember their customers very well and track stuff mentally using their names, it’s more important to highlight that there are people behind these transactions. These merchants have chosen to use Instamojo because they want a direct relationship with their audience, so we should help them feel this relationship.

---
## Design & Prototyping

After many white-boarding sessions and iterations, we finalised the overall purpose of the app and the main dashboard contents. The dashboard is designed to be the go-to place for merchants to track their sales in the last day/week/months and hence that’s the primary focus on the screen. Along with the sales numbers, we also showed numbers that indicate growth/dip in business compared to the previous day/week/month.  

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_sales.jpg" />
</figure>

---

Another objective of the andriod app was to enable merchants to create and share payment links and products directly from the app. Since we saw usage patterns in sharing via Whatsapp, Email and Facebook, we made it easy for merchants to share their links/products on these platforms directly from the app. Prior to this, merchants would copy-paste links into mails and whatsapp manually on the desktop/browser.

---

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_instamojo_links.jpg" />
</figure>

---

While the project was onto the development phase, I carved out time to make details within the app, animations, empty states via prototypes, to help convey some animations and interactions to the developers and how this plays a role in customer delight.


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

This was beyond the scope of this project, but the team had future visions of helping merchants manage their capital & shipments. While working on these designs, I realized how difficult it can be for merchants with larger audiences to manage their capital & shipments. SMBs usually struggle with liquidity on a daily/weekly basis that can aid their procurement or fulfilment of the orders. Instamojo has later taken this business challenge up and launched mojo-express and mojo-capital.

### Track your sales wherever you go. <a href="https://play.google.com/store/apps/details?id=com.instamojo.app&hl=en_IN">Download Instamojo from the Play Store</a>.
