---
layout: post-no-feature
title: SaaS Billing and Pricing
description: "How I underestimated the complexities of a billing system."
categories: articles
date: 2013-08-21
comments: true
---
My first release of [Bespeak](https://www.bespeak.io), was simple. $10/mo, unlimited everything! How could they not want that? Same price as the most basic plans my competitors were offering, but included **every feature**. 

Why didn't people like this? 

My first mistake was ignoring every pricing chart I have ever seen. I honestly thought people would prefer honest, simple, fair pricing.

> People don't prefer honest, simple pricing.

Humans don't work this way. Give them one option, and they will feel like the deal is one sided. Give them a few options, and they turn into bargain hunters. It has measurable effects.

I was stupid, and decided to ignore countless studies, hundreds of past experiences and instead, decided to wing it. 

###Charm Prices
My second mistake was using a round number ($10/mo); I hear you saying "James, I fucking hate prices that end with .99, it is bullshit!". I know, yet it is everywhere, nearly every business uses charm pricing, why? Countless studies have been done, and have proven that charm pricing is effective in creating more sales than rounded prices. Don't be me, _educate yourself_.

<figure>
    <iframe width="100%" height="400" src="//www.youtube.com/embed/nZqOGhWw3Q8" frameborder="0" allowfullscreen></iframe>
</figure>

###Pricing Tables
The upside to having a fixed monthly cost, is reduced complexity. It benefits me directly, and is a great way to get out of the MVP stages of a product. But remember, it does not benefit the customer, or your bottom line. It should be the first thing you do, and always be part of the architecture from the beginning. Because:

> Billing, and feature splitting is hard.

This is a very easy mistake to make; when you start a new project you don't think about the **sweet billing system**! But I'm telling you now, you have to. It should be baked in from the start. Every feature should be able to be turned on and off, per user, per plan, per whatever. Make this configurable now, and you'll save yourself a metric shit ton of time.

<figure class="effect6">
    <a href="https://www.bespeak.io/pricing"><img src="/images/pricing.png" alt="Bespeak Pricing" /></a>
</figure>

> Customers want choice.

###Freemium
I've read a lot on the pros/cons of a freemium model, and while I have not come to a direct conclusion I decided to go with a Freemium model for [Bespeak](https://www.bespeak.io/).

It costs me nothing to support my free users, because I don't let them use any features that directly cost me money. This is important, if you are going to give free users access to features that cost you money you **have** to limit them. I'm too lazy to writing code to account for that shit. Bottom line, don't pay for your free users.

If you give your free users a good reasonable taste, some will want or need more and you will get an upgrade!

> Freemium, the heroin of the internet.

