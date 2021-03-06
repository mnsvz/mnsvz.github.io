---
layout: article
title:  "Redesigning Swiggy Consumer Apps"
date:   2015-03-09 13:57:09
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


In early 2015, Swiggy had to ramp up their growth and at the time online food ordering experience in India was in bad shape. Hungry users had to go through broken checkout flows, deal with ill-managed addresses and wait impatiently on a dumb & opaque delivery process.

We wanted to change this and make food-ordering 'second nature' to our hungry users. Often times, these hungry users were placing orders via Swiggy daily. We'd conducted multiple interviews with some of Swiggy's most loyal customers regarding their daily food ordering habits and the issues they were facing. 

One of the key insights we got from our research was that, people go through a lot of anxiety in ordering and waiting for their food. Hunger is one of the primal needs for us human beings. Evolutionary psychology also tells us that, hunger is designed to induce anxiety and fear when deprived of food thereby leading to better chances of survival. Our conversations (both on call and in-person) with these users also led us to areas of improvement within the product experience that would enable customers to be in control of their orders and hence reduce the anxiety. 

During the second half of 2015, I led the redesign of Swiggy's consumer apps to get rid of the hassle in food ordering UX and standardise the communication of the underlying logistics to the users. Here are just a few of the changes we shipped.  


## Live Tracking and Logistical Transparency.


Many users told us, they were very anxious about the "current status" of their food delivery more than anything else. Previously, the track order feature was not visible and was accessible only via the order details page. Many users would navigate into these pages to find the track order CTA to track their ongoing order.


<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_tracking.jpg" />
</figure>

---

We eliminated this manual effort by implementing 'live tracking' via google maps and surfacing the map screen to the top most level. Every time a user had an active order, live tracking became the default screen and was always opened on app launch.

Along with the tracking, we also had to standardise the communication around logistical milestones for a Swiggy order. We found that users felt more in-control of their orders when Swiggy's logistical efforts were communicated to them in real-time and clearly. We identified 4 important milestones that corresponded to most common worries a Swiggy user had during an active order.

1. Order confirmed by the restaurant
2. Delivery person assigned/arrived at the restaurant
3. Food is en-route to delivery and
4. Order delivered

Along with exceptional delivery time SLAs mantained by Swiggy, standardising these steps across orders helps users develop a muscle memory of the usual process and makes food ordering easy and habitual.

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_stages.jpg" />
</figure>

---



## Get me the food, where-ever I am

Adding a new delivery address and managing existing addresses was manual and a pain for the users. We advocated for auto-filling the address fields via google maps. This made the ‘add a new address flow' more accurate and easy for the users. Coupled with the training efforts, this accuracy further helped the logistics/operations teams to perform better, by eliminating many last mile phone calls between users, delivery personnel and Swiggy’s customer care.


<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_address.jpg" />
</figure>

---

During user interviews, we observed that people think of delivery locations as "home" or "office", we then designed quick tags such as “home”, “office”. This made it easier for users to be sure of their current delivery location. We also developed a feature logic, based on the location and time of the day - the app automatically fetches the right address and gives the list of restaurants. Thereby eliminating manually choosing the address every time.


## Increasing the 'Average Order Value'

One of the business goals for design, was to help raise the median-order-value of an order from Rs. 150 towards Rs.250. This further led to effective efforts in optimising the delivery fleet and its operational costs. 

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_cross_sell.gif" />
</figure>

---

We teamed up with folks from the product and data intelligence teams and analysed every food item from all restaurants and created a relational database of “main dish” + “accompaniments” (Like Biriyani + Cold Drink or Ice cream). We also started recommending some items on the Cart screen and food customization screen to 'cross sell and ‘upsell’ beverages/ice creams, the relevance of the accompaniments led to an increased order value and over time, reach the median order value of Rs 250 per order.

---


## Food-first onboarding and signup

When Swiggy was first introduced on mobile, users were asked to signup and login via email and/or phone number. This led to two separate flows where some set of users logged in via passwords and others used the OTP SMS service to log in. This also introduced un-intended password storage issues and we saw many users would forget their credentials and were not able to sign in.

<figure>
<img class="lazy" data-original="{{edchao.github.io}}/assets/img_swiggy_onboarding.jpg" />
</figure>

---



Through preliminary testing we deduced that users just wanted to decide on the food first and then worry about authentication. The product and tech team at Swiggy got on a sprint and re-worked user accounts internally, this enabled us to release a single log-in method (via OTP) for all users across iOS, Android and Web. We also took a decision to load the app with restaurant listing by default and prompted users to login when they had made their choice on food/restaurant and were ready to place the order. This further lead to decrease in the numbers of abandoned carts and made it easier for users to complete orders across platforms like web/android/ios.

---
## Future Track

Since 2016, Swiggy has championed customer experience and scaled their food delivery business across major cities in India. With a focus on delighting their customers, they remain the leading startup/product in the food delivery sector. They have continued to build on the core value proposition and launched many successful initiatives like cloud kitchens(bowl company, homely) and Swiggy Pop, a food first approach that makes it even easier for the users to get food delivered ASAP.

---

### Lightning fast food delivery. <a href="https://itunes.apple.com/in/app/swiggy-food-order-delivery/id989540920?mt=8">Download Swiggy from the App Store</a>.
