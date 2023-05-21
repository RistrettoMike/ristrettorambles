---
title: "Upgrading & Settling-into the ThinkPad t480"
date: 2021-11-28T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
#tags: ["about"]
author: "Ristretto"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
#description: "Some impressions of the ThinkPad t480 & a host of upgrades I made to mine."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: true
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: false
#ShowPostNavLinks: true
cover:
    image: /images/t480post/desk.jpg # image path/url
    #alt: "<alt text>" # alt text
    #caption: "Some impressions of the ThinkPad t480 & a host of upgrades I made to mine." # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
    linkFullImages: true
#editPost:
    #URL: "https://github.com/<path_to_repo>/content"
    #Text: "Suggest Changes" # edit text
    #appendFilePath: true # to append file path to Edit link
---

### *Author's Note* 
*This piece was originally written and published to Reddit on 11/8/2020, but is the only piece of writing I've spent any real time on in recent memory prior to starting this blog.*

*I'm still acquainting myself with how to properly format & post using Hugo, so I figured porting-in this piece would be a good way of working out any formatting/publishing kinks before starting work on original pieces for RistrettoRambles. The writing here was written with a different context in mind, but I hope it's still vaguely interesting to read over anyways. ~M*

--

Hey folks,

I only recently became a ThinkPad fan earlier this year after searching for & finding the excellent value of an x230 with a handful of upgrades thrown in. Pretty quickly I got used to some of the ThinkPad design mainstays you could still see in that model with its' sturdy build, excellent input methods, and emphasis on user-serviceability.

A little while after that I got the chance to trade a fixed-up x230 + some cash for the t480 you see below. It felt like rolling the dice on if a newer, larger ThinkPad would be a good fit for me, but I still pulled the trigger on it. This is a few months ago now, and I'm very glad I did.

![overview](/images/t480post/overview.jpg)

## Stock Impressions:

The t480 came to me with the stock Intel i5 8250u CPU, 16GB of RAM, a 500GB SATA SSD, stock 1366x768 TN Panel, non-backlit keyboard, and a flush 3-cell battery. Pretty decent deal for a trade & some extra dosh, but I was looking forward to making some improvements and trying out the machine proper.

![sizecompare1](/images/t480post/sizecompare1.jpg)

![sizecompare2](/images/t480post/sizecompare2.jpg)

Coming from an x230 (and prior to that an older 11" MacBook Air) I was a little concerned that the t480 would feel too large for my daily use. It's heavier in a "dense feeling" way, and requires a larger space in bags, but I've come to appreciate the extra space to stretch out and work both onscreen and on the keyboard deck + palmrest. I'd probably swap to a 12.5" or 13.3" device if there was one that boasted the t480's  features and expandability, but because there isn't I'm quite happy continuing to acclimate to a larger workhorse.

The build overall feels more premium but also a bit more fragile than the ThinkPads I've fixed up and owned from around the x230's release period. Those machines were finished less lavishly but felt like you could throw them around without damaging the internals inside. The t480 feels nicer, but also so densely packed that it's hard to imagine you wouldn't crunch in on something important with a decent drop. Its' finish also collects a lot more hand oil on the outer case, which I'm trying to let bother me less over time.

The t480's ports are more than enough for my use cases daily. I moved to USB-C chargers for my phone and x230 not long ago, so the t480 fits right in. The rest of the I/O is versatile and nice to have. USB-C/Thunderbolt 3, USB-A, HDMI, Ethernet, full-size SD, and a 3.5mm jack feels like as many options as one could want outside of dedicated audio in + out jacks. My want for that stems specifically from my livestreaming hobby though. I won't need to use everything here on a regular basis, but I'm grateful the functionality will be there when and if I do.

While using the machine the performance jump coming from a 3rd-gen dual core up to an 8th-gen quad-core Intel CPU was  evident. I don't tax my CPU heavily on most days, but even in general system usage, light mutlitasking, and a good amount of web browsing things felt snappier and the system ran cooler than my x230 ever could. 

![undervolt](/images/t480post/undervolt.jpg)

### Undervolting:

This segues us nicely into undervolting, which was something new for me to learn with this machine. [I learned from this guide](https://www.ultrabookreview.com/31385-the-throttlestop-guide/) and had a fun time dialing in the undervolt values & stability using Throttlestop, [a looping Cinebench R20 script](http://forum.notebookreview.com/threads/cinebench-r15-r15-extreme-r20-command-line-syntax-bat-loop-detailed-output.815101/), and RealBench for extended stress testing. It's really cool seeing how the voltages, clockspeed, TDP, and temperatures all relate and react to one another. After a week of trying different values on both AC and Battery I settled on a -160mv undervolt for the core+cache and a -55mv undervolt for the iGPU+unslice. This handily dropped operating temperatures and allowed for eking out a bit more performance under sustained load.

Having gotten mostly used to the size and invested some time tweaking the machine to make it run better, I was enjoying the t480 enough to begin ordering parts and upgrades in for the machine - these will comprise the real meat of this post;

--

## The Upgrades:

![igzo1](/images/t480post/igzo1.jpg)

![igzo2](/images/t480post/igzo2.jpg)

### Innolux IGZO Low-Power FHD Panel

This is a phenomenal screen that's likely the best panel I have in a device at this point. Especially coming from the underwhelming stock TN panel this display has made using the t480 a lot more special. I can tell I'm looking at a high quality panel each time it flicks on and I see the Lenovo logo or my desktop wallpaper. Colors and blacks simply pop ([NotebookCheck reviewed this panel here](https://www.notebookcheck.net/Lenovo-ThinkPad-T495-Review-business-laptop-with-AMD-processor-long-battery-life-and-good-display.434716.0.html#toc-display)), & all that alongside the high 400nits brightness and reduced power draw is just a treat. This is also my first time using a 1080p panel in a 14" screen, and I find things to be a good balance of spacious, readable, and crisp at 125% scaling. 

Ensuring to get the IGZO panel made by Innolux means you'll get all the aforementioned niceties without compromising on more intense ghosting like with some of the other IGZO FHD panels from BOE & AUO. [I had good luck sourcing a genuine panel with this seller](https://www.ebay.com/itm/72-color-N140HCG-GQ2-fit-N140HCG-GR2-NE140FHM-N61FOR-T490-T495-T460-T470-T480/174392007344?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2057872.m2749.l2649) on eBay who mention including the proper panel-mounting-brackets in their listing, and also reached out to me upon placing my order to confirm their panel would be compatible with my device. It took a few weeks to show up, but it was so worth it. Allow yourself some time to sit down and gradually remove the bezel so you don't kink it and its' adhesive strips like I did, and you'll be golden.

![keyboard1](/images/t480post/keyboard1.jpg)

### Chicony Backlit Keyboard (FRU 01HX419)

The keyboard turned out to be a pretty finicky upgrade for me. I didn't mind the non-backlit Darfon-manufacture model's keyfeel - it has a slightly more pronounced "snap-back" after depressing a stroke - but I did mind the cheaper looking & feeling keycaps with decal legends. It took me *three* orders of a backlit replacement part to receive one that functioned properly on arrival. The first one was warped in a way that made the spacebar miss 75% of my inputs unless I forcefully bottomed out the right side, and the second had perfectly functional keys but a non-functional TrackPoint + mouse buttons. It took until the third one for me to get in a Chicony-manufacture model with good keys & TrackPoint operation out of the box.

![keyboard2](/images/t480post/keyboard2.jpg)

![keyboard3](/images/t480post/keyboard3.jpg)

As mentioned above, the backlit keyboard does feel slightly different from the non-backlit model in typing dynamics. It seems to have the same amount of tactility and force required for a keypress, but springs back afterward ever so slightly softer & quieter. I don't feel a huge difference in use, but I do give a slight edge to the feel of the non-backlit model. The keys of the backlit keyboard are made of a higher quality material and have legends formed into the keys themselves to allow the backlight to shine through. The backlight itself isn't as bright or as clean as other laptops I've seen, but I appreciate having the option there when I need it.

![trackpad](/images/t480post/trackpad.jpg)

### X1 Extreme Glass Trackpad

This was one of my final upgrades. It was [a relatively cheap part + long wait to order from AliExpress](https://www.aliexpress.com/item/4000597668364.html?spm=a2g0s.9042311.0.0.18414c4dQ9PQTj) and dropped in as an easy replacement after a little fiddling to get the trackpad properly centered in its' space.

I use the TrackPoint for most mousing duties, but enjoy the trackpad for gestures throughout Windows or for when I can't use both my hands while using the machine. The glass surface is smoother than the plastic trackpad but still has a very fine, matte texture finish to the surface. 

I've already put a few hairline scratches in mine somehow, which is something I didn't think about happening with glass but totally does. Still, I'm happy the surface I interact with there will likely stay fresher looking and nicer feeling over time than plastic would.

![trackpoint2](/images/t480post/trackpoint2.jpg)

### SaotoTech low-profile soft-rim TrackPoint Cap

I came to prefer the soft-rim style TrackPoint while using my x230 earlier this year, [so this 3D-printed version from SaotoTech's Etsy shop](https://www.etsy.com/listing/707617816/low-profile-softrim-type-trackpoint-caps?ref=shop_home_active_3&crt=1) for newer, slimmer ThinkPads was an instant order for me. 

![trackpoint1](/images/t480post/trackpoint1.jpg)

![trackpoint3](/images/t480post/trackpoint3.jpg)

It took awhile to ship overseas but was worth the wait. The material is slightly tougher feeling than the stock soft-dome cap, but recaptures the sensitivity and finger-anchoring that I appreciate with the official soft-rim caps. A cheap way to enjoy your TrackPoint even more & support a ThinkPad fan's shop. :)

![ssd](/images/t480post/ssd.jpg)

 ### m.2 2242 NVMe SSD

This t480 is the first machine I've owned that accepts NVMe storage, so I was excited to add in the Western Digital SN520 512GB NVMe SSD (the one that comes from the factory in the 2242 size, [y'all are some real ones for manually slicing SSDs in half.](https://old.reddit.com/r/thinkpad/comments/jiqht7/cant_find_2242_nvme_ssd_cut_a_2280_in_half_t480/))

I wasn't able to find many options for NVMe SSDs in the 42mm "2242" size, so after shopping around [I picked up my SN520 from TigerDirect](https://www.tigerdirect.com/applications/SearchTools/item-details.asp?EdpNo=5873766&CatId=5303) who shipped it out extremely quickly. It benchmarks a good deal faster than the average speeds from the Crucial 500GB SATA SSD that came with the t480, but I'm not doing anything overly intense with it. It boots a touch quicker than my SATA SSD did (usually before the little Windows spinner can finish a full circle animation) and leaves room for future expansion in the t480's 2.5" bay - so I'm pleased with the purchase.

Here's some quick CrystalDiskMark results to test out the new SSD. First is the Crucial MX500 SATA SSD that came with the t480:

![ssd2](/images/t480post/ssd2.PNG)

And after that, here's the boosted speeds from the SN520 2242 NVMe SSD:

![ssd3](/images/t480post/ssd3.PNG)

Pretty nice :)

![battery1](/images/t480post/battery1.jpg)

![battery2](/images/t480post/battery2.jpg)

 ### 72Wh 6-Cell Battery

I felt intimidated by the dearth of sketchy "genuine compatible" t480 batteries on eBay, so I ordered mine [straight from Lenovo through Amazon](https://www.amazon.com/Lenovo-Battery-4X50M08812-Retail-Packaged/dp/B06WGMPFCD/) and called it a day.

The stock setup of external 3-cell battery + internal 3-cell battery gave me around 4-6 hours of mixed usage with a few utilities running, Discord open, 3-6 Firefox tabs, and some light video and music playback.

![battery3](/images/t480post/battery3.jpg)

On the 72Wh 6-cell battery + 3-cell internal I routinely use my computer for upwards of 6 hours at work and still pack up the machine with 50% or more left to go. I was expecting the combination of a low-power display, undervolted CPU, and extended battery to be potent - *just not quite this potent*. Anywhere from 10 to 14 hours of screen-on time is just insane to me. It's a tossup between the IGZO display and this battery for my favorite upgrade.

![heatsink](/images/t480post/heatsink.jpg)

 ### dGPU Heatsink + Fan Assembly

This was the last upgrade I added to the t480, and was [another cheap part + long wait from AliExpress](https://www.aliexpress.com/item/4000670899792.html?spm=a2g0s.9042311.0.0.18414c4dQ9PQTj). My t480 lacks the dedicated Nvidia MX150 dGPU, so I isolated the part of the heatsink that would normally make contact with it using some electrical tape and re-pasted the t480 at the same time with some Kryonaut thermal paste I had left over from re-pasting my x230.

In the small bit of testing I've done since, working temps have dropped to around 30-40C while idle with programs open, and 45-55C while browsing, watching video, and general light multitasking. 

Here's a shot of the temperatures while idle:

![idle](/images/t480post/idle.png)

And another screenshot this time running Cinebench:

![cinebench](/images/t480post/cinebench.PNG)

The idle temps are pretty nice, but I was even more impressed upon looping Cinebench R20 and monitoring in Throttlestop. The upgraded heatsink allows the t480's i5 8250u to maintain a 3.0-3.1Ghz boost clock indefinitely while accepting a 25W sustained TDP & hovering around 73-75C. That's an increase from it settling in at around 2.6-2.7Ghz and around 19W sustained TDP on the stock heatsink and its' similar to slightly higher temps. This netted a tidy increase in Cinebench results from ~1330 with the stock heatsink up to ~1580 with the dGPU heatsink. Not bad for a $15 part, and if one was really into tweaking thermal limits there's room to extract even more performance for your effort while still staying under 80C.

--

## Post-Upgrade Impressions:

Having invested so much time and effort into upgrading this t480 one would hope that I end up preferring it to my prior x230 - and indeed I do. The t480 strikes a nice balance between newer quad-core performance on a power-sipping CPU, a host of tweaks & upgrades that can be swapped in mostly painlessly, and a good selection of ports that'll allow for both backwards *and* forwards compatibility for awhile to come. The overly nice display panel & impressively long battery life were the main two factors that pushed the t480 over the edge into being my daily machine.

The things I end up missing most from my x230 are its' x220-swapped classic 7-row keyboard and its’ more old-school ThinkPad design + sensibilities. At some point along the way ThinkPads became more like MacBooks that still sport some distinguishing ThinkPad features rather than a wholly distinct product, but that doesn't mean the newer ThinkPads aren't still great to use.

I don't even miss the x230's compact size as much as I thought I would. I'd still take a hypothetical device sporting a 16:10 or 3:2 aspect ratio & falling between the t480 & x230's sizes as a personal ideal, but I appreciate what the t480 packs into its' footprint all the same.

![desk](/images/t480post/desk.jpg)

After months of upgrades I feel quite settled into my little t480 build. I still have the potential to upgrade up to 32GB of RAM and chuck a larger SATA SSD into the 2.5" bay if ever needed, but for now I think my season of upgrades is done. 

I've come to like this little machine enough to think about replacing my desktop altogether with it, so maybe that's where my further upgrades will manifest. And come to think of it, [Xyte.ch 's T25 classic keyboard modkit does look pretty tempting](https://xyte.ch/shop/t25-frankenpad-kit/)... I just can't justify the cost... yet ;). There I go again.

![theend](/images/t480post/theend.jpg)

Anyways. If you've made it this far down the page thanks for reading and I hope you enjoyed seeing the different things I chose to add to my ThinkPad. This community of fixer-uppers, mods, and upgrades is a lot of fun - hope y'all appreciate whatever ThinkPad machine you've chosen to rock.

Cheers,

~M