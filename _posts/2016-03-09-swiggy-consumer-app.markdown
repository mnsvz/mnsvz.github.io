---
layout: article
title:  "Redesigning Swiggy Consumer Apps"
date:   2018-03-09 13:57:09
headline: "Redesigning Swiggy Consumer Apps"
co: "Swiggy"
tags:
- ui
- interaction
categories:
- published
---
<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_cover.jpg" />
</figure>

<!--more-->
---

## Lightning fast food delivery, made simple.


In early 2015, Swiggy had to ramp up their growth and at the time, online food ordering experience in India was in bad shape. Hungry users had to go through broken checkout flows, deal with ill-managed addresses and wait impatiently on a dumb & opaque delivery process. Often times, these hungry users were placing orders via Swiggy daily.

We wanted to change this and make food-ordering 'second nature' to our hungry users.
During the second half of 2015, I led the redesign of Swiggy's consumer apps to get rid of the hassle in food ordering UX and standardise the communication of the underlying logistics to the users. Here are just a few of the changes we shipped.  

<!--more-->
---

## Live Tracking and Logistical Transparency.


We kept seeing overwhelming evidence that suggested, users were very anxious about the "current status" of their food delivery. Previously, the track order feature was not visible and was accessible only via the order details page. Many users would navigate into these pages to find the track order CTA to track their ongoing order.


<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_tracking.jpg" />
</figure>

---

We eliminated much of the anxiety by implementing 'live tracking' via google maps and surfacing the map screen to the top most level. Every time a user had an active order, live tracking became the default screen and was always opened on app launch.

Along with the tracking, we also had to standardise the communication around logistical milestones for a Swiggy order. We idenitifed 4 important milestones that corresponded to most common worries a Swiggy user had during an active order. 

1. Order confirmed by the restaurant
2. Delivery person assigned/arrived at the restaurant
3. Food is en-route to delivery and
4. Order delivered


<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_stages.jpg" />
</figure>

---




## Better Address Management

Adding a new delivery address and managing existing addresses was manual and a pain for the users. We advocated for auto-filling the address fields via google maps. This made the ‘add a new address flow' more accurate and easy for the users. This accuracy further helped the logistics/operations teams to perform better, by eliminating many last mile phone calls between users, delivery personnel and Swiggy’s customer care.


<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_address.jpg" />
</figure>

---

Aiding to the repeated usage, we also created quick tags such as “home”, “office”. This made it easier for users to know their current delivery location. We also developed a feature logic, based on the location and time of the day, the app automatically fetches the right address and gives the list of restaurants. Thereby eliminating manual choosing of the address every time.


---


## Increasing the 'Average Order Value'

One of the business goals for design, was to help Swiggy raise the median order value of a user from Rs. 150 towards Rs.250. This further led to effective efforts in optimising the delivery fleet and its operational costs.

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_cross_sell.gif" />
</figure>

---

We teamed up with folks from the product and data intelligence teams and analysed all food items from all restaurants and created a relational database of “main dish” + “accompaniments” (Like Biriyani + Cold Drink or Ice cream). We also started recommending some items on the Cart screen and food customization screen to ‘upsell’ beverages and ice creams, the relevance of the accompaniments led to an increased order value and over time, reach the median order value of Rs 250 per order.

---


## Food-first onboarding and signup

When Swiggy was first introduced on mobile, users were asked to signup and login via email and/or phone number. This led to two separate flows where some set of users logged in via passwords and others used the OTP SMS service to log in. This also introduced un-intended password storage issues and we saw many users would forget their credentials and were not able to sign in.

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_onboarding.jpg" />
</figure>

---



Through intial testing we figured out that users just wanted to decide on the food first and then worry about authentication. The product and tech team at Swiggy got on a sprint and re-worked user accounts internally, this enabled us to release a single log-in method (via OTP) for all users across iOS, Android and Web. We also took a decision to load the app with restaurant listing by default and prompted users to login when they had made their choice on food/restaurant and were ready to place the order. This further lead to decrease in the numbers of abandoned carts and made it easier for users to complete orders on web or phone.

---

---

### Lightning fast food delivery. <a href="https://itunes.apple.com/in/app/swiggy-food-order-delivery/id989540920?mt=8">Download Swiggy from the App Store</a>.
