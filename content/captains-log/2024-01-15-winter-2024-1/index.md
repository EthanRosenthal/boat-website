---
title: "2024 Winter Projects Part 1"
slug: 2024-winter-1
date: 2024-01-15
---

Between the holidays and some time off in between jobs, I got to spend a significant (for me) amount of time working on Peregrine. I was very thankful to have Peregrine in Jersey City. It was also weirdly surreal to sit on a boat, in a parking lot, with high rise apartments around you and a view of the World Trade Center.

{{< figure src = "ladder.jpg" caption = "Peregrine in a parking lot" width = 400 >}}

At the start of the winter season, I wrote down a list of projects to work on. This list got immediately derailed.

## The Bilge

I did not have any bilge work on my list, but then I discovered that neither my electric nor my manual bilge pump worked on my first winter day down at the boat. The pipe for the electric pump was cracked. The manual pump didn't provide any suction. I couldn't get the manual pump out from where it was mounted on the deck because the bolts were seized. And then, I ripped a giant hole in my jeans. Not the best way to start the winter.

{{< figure src = "the_bilge_1.jpg" caption = "The bilge. The Series 141 hose attached to the Rule-Mate 2000 bilge pump is cracked" width = 400 >}} 
{{< figure src = "manual_hole.jpg" caption = "Trash bags covering the hole where the manual bilge pump is stuck." width = 400 >}}
{{< figure src = "salt_in_the_wound.jpg" caption = "Salt in the wound" width = 400 >}}

Thankfully, I had a pair of gym shorts on the boat that I could wear on the PATH train home.

In the end, I got everything working. I replaced the cracked electric bilge hose (after first buying the wrong size). I bought an impact driver to I could remove the manual bilge pump, a Gusher 10 Mk3. I brought this pump home, and it was absolutely disgusting inside.  

{{< figure src = "gusher10.jpg" caption = "The Gusher 10 Mk3 bilge pump" width = 400 >}}
{{< figure src = "gusher10_inside.jpg" caption = "The inside of the Gusher 10." width = 400 >}}

I ordered a [service kit](https://www.fisheriessupply.com/whale-spares-service-kits-for-bilge-pumps/ak3706) with new gaskets and whatnot from Fisheries, along with a new [deckplate gaiter kit](https://www.fisheriessupply.com/whale-deckplate-gaiter-kit/as3725). While it cost me $90 for these service kits, it would've been $410 for a new bilge pump. It's worth it to fix the pump! 

Cleaning the manual pump was gross, but it was pretty quick to replace the gaskets. I had ruined the old bolts trying to remove the pump, so I bought new ones and made sure to coat the ends with Lanolin to avoid future seizing. I got the pump installed, and was very happy when it worked right off the bat.

{{< rawhtml >}}
<video width=100% controls autoplay>
  <source src="pumping_the_bilge.mp4" type="video/mp4" >
  Your browser does not support the video tag.
</video> 
{{< /rawhtml >}}


## Plumbing

As I was poking around the boat, I lifted up the port settee and looked at the holding tank and plumbing underneath. This smelled kinda bad down there, and then I noticed that the air vent port in the holding tank was cracked. Shit.

{{< figure src = "cracked_vent.jpg" caption = "Cracked holding tank air vent port" width = 400 >}}

I got some Boat Caulk, Silicone Rescue tape, and a hose clamp and attempted to seal the whole thing up. We'll see if that helps. I'm somewhat nervous about the smells down in that locker, so I'm wondering if I'll need to do some more replacing of hoses next winter :/ 

{{< figure src = "silicone_vent.jpg" caption = "Caulked and taped vent" width = 400 >}}
{{< figure src = "hose_clamp_vent.jpg" caption = "With a hose clamp" width = 400 >}}

While I was at it, I drew a plumbing diagram to convince myself that closing the seacock by the head should have made the sewage smell disappear (it shuts off any hose connection between the holding tank and the sea.).

{{< figure src = "plumbing_diagram.jpg" caption = "Plumbing diagram" width = 600 >}}



## Electrical

One of my goals was to get a better handle on the boat's electrical systems. The connector block was a mess of unlabeled wires. Many the wires were "vestigial"; they weren't even used anymore. For example, the three instruments above the connector block were all for the boat's original engine, not the current Beta engine. I labeled a bunch of wires, removed wires that weren't used anymore, and generally did a bit of refactoring along the block. 

{{< figure src = "unlabeled_connector_block.jpg" caption = "Connector block before" width = 600 >}}
{{< figure src = "labeled_connector_block.jpg" caption = "Connector block after" width = 600 >}}

During this process, the thin sheet of wood to which the connector block is attached delaminated from the thick piece of wood that's attached to the fiberglass. This was somewhat fortuitous since the connector block is difficult to access in its standard position. I ended up using some wood screws to reattach the wood sheet, but I'd like to move the whole thing above the old instruments for easier future access.

I tested electricity of various systems on the boat. There aren't that many systems (and in particular no refrigeration), so current draw is pretty low. Still, there are two halogen lights above the galley and head sink which each draw almost a full amp. I replaced the halogen bulbs with [these](https://www.amazon.com/dp/B08YMWF6BY) G4 LEDs that draw 10X less at like 95 mA.

{{< figure src = "led.jpg" caption = "LED above the head sink" width = 400 >}}

All season, I suspected my second battery was dead. The previous owner suspected it had been dead, too. I wanted to get my batteries tested, and buy new ones if need be. To start, I needed to figure out what the hell was going on with my battery setup to begin with. So, I labeled all the wires going into the battery box. I eventually learned that the `???` wires were the GPS system that plugs directly into the batteries.

{{< figure src = "unlabeled_batteries.jpg" caption = "Unlabeled batteries" width = 400 >}}
{{< figure src = "labeled_batteries.jpg" caption = "Labeled batteries" width = 400 >}}

I then rented a Zipcar to try to find some replacement AGM Group 34M batteries. There are not many obvious options for marine batteries near Jersey City. BJ's actually had some, but not in my size. I asked if they'd test my batteries, and they gave me a hard No. I ended up going to Advanced Auto Parts. They had Group 34M batteries, but not at that store. They said they could get them first thing in the morning the next day. 

The next day, I went to rent the _exact same_ Zipcar that I had rented the day before. After I booked the car, the people working at the parking lot told me that the Zipcar had failed to start after I had dropped it off the day before. They'd had to manually move the car into a parking space. They'd told Zipcar who had done nothing about it and still left this car as bookable in their app. Sure enough, it wouldn't start for me. After 10 minutes chatting with Customer Support, they booked me a different car. I honked the car's horn using the app so that I could find it. The parking lot attendants immediately told me that my new car had not been able to be unlocked for weeks. They'd told Zipcar who had done nothing about it and still left this car as bookable in their app. Another round of Customer Support, and my third car finally worked. 

Anyway.

I got my old batteries tested (number 2 was, in fact, dead), bought the new batteries, lugged them up my ladder, installed them, and everything worked! I was as surprised as you.

{{< figure src = "bjs.jpg" caption = "Absolutely nobody to be found at BJ's" width = 400 >}}
{{< figure src = "big_blues.jpg" caption = "Some new blue tops" width = 600 >}}
{{< figure src = "new_batteries.jpg" caption = "The new batteries" width = 400 >}}
