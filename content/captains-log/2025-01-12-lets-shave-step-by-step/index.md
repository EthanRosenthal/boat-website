---
title: "Let's shave step by step"
slug: lets-shave-step-by-step
date: 2025-01-12
---

In most STEM classes, you do not get full credit for solely providing the correct answer to a homework or test question; you must show your work. Explaining your thought process reveals whether you actually understand what's going on.

One of the stupidest breakthroughs for Large Language Models (LLMs) a couple years ago was the "discovery" of Chain-of-Thought reasoning. Specifically, some researchers found that you were more likely to get a correct answer to your question if you first fed a special phrase into the LLM's mouth: "[Let's think step by step](https://arxiv.org/abs/2205.11916)". This prompted the LLM to show its work, which somehow made it provide more accurate answers. 

I recently had a pretty bad issue on Peregrine. The engine started dying. Without providing any other information, if I were to ask you why this was happening, what's your first thought? You will probably reach for [Occam's razor](https://en.wikipedia.org/wiki/Occam%27s_razor), and snarkily say, "Uhhh did you not have enough fuel?". 

And you know what, you'd be right. 

But, while you quickly found the answer, you probably didn't find the _reason_. When debugging things, whether they be boats or bits, finding the answer isn't good enough. We need to understand _why_ if we want any hope of squashing the bug long-term.

## The Fuel Story

Even though the beginning of the Sabre 28 manual claims that the boat has a 22 gallon fuel capacity, the fuel diagram on I-17 says that the boat only has a 20 gallon Miramax #AH20C Rogal tank. I believe that Peregrine has this original fuel tank. What Peregrine does not have is a working fuel gauge. The fuel gauge is hooked up to the old, original engine instruments. These instruments are now vestigial, since Peregrine has a newer Beta Marine 16HP engine with its own instruments. 

Until now, lacking a fuel gauge hasn't been an issue. Each time I take the boat out, I write down the date and the engine hours. I don't actually know Peregrine's fuel consumption, but I know that I don't use the engine enough to require filling up mid-season. I sailed the whole 2023 season and only refilled before hauling the boat for the winter.

This is why I was confused on the Saturday of Labor Day Weekend when the engine started to sputter and stall out while motoring back to the mooring from Sands Point with friends and family on board. The RPMs would randomly drop. Sometimes the engine would turn off, while at other times the RPMs would come back up, like a tachometric whipsaw. 

We managed to make it back to the mooring, but I was confused. I had multiple estimates that all indicated that I ought have roughly a half of a tank of fuel:

1. The previous summer, I ran the engine for 17 hours. At the end of the summer, I filled up 5.6 gallons of diesel, which comes out to 0.33 gallons / hour. I admittedly ran the engine a bit slow towards the beginning of the summer (probably closer to 2200 RPM vs 2550 RPM which I usually run it at).
2. The fuel consumption diagram for my Beta 16HP shows ~1.3-1.4 liters / hour aka 0.34 - 0.37 gallons / hour at 2500 RPM. This is inline with the above estimate of 0.33 gallons / hour, considering I was running lower RPMs the previous summer.
{{< figure src = "beta_consumption.png" caption = "Fuel consumption for the Beta 16HP" width = 400 >}}
3. So far this summer, I had run the engine for 28.6 hours which comes out to only 10.6 gallons @ 0.37 gallons / hour. 

So by all estimates, I should have ~9.4 gallons in the tank which ought to be plenty. What's the deal?

Alas, we had to get back to the city at this point, and I'll tell ya that it doesn't feel good to abandon your boat without a working engine or a clue as to why.

## Diesel Red Herrings

The worst part about the weeks that followed, in which I struggled to diagnose the root issue, was that the Fall weather was absolutely _perfect_ for sailing.

With some now-standard help from my Dad, we assumed that the engine was failing to get fuel for some reason. I first replaced the fuel filter/water separator filter, but that did nothing.

{{< figure src = "water_separator.JPG" caption = "Fuel filter / water separator" width = 400 >}}

I then thought I caught a lucky break. One of the traveler lines happened to be covering the air intake for the fuel tank. Perhaps fuel couldn't flow since air couldn't come in to fill its place? This theory also lined up nicely with the fact that the problem started _after_ we had gone swimming off the back of the boat right by the air intake. 

{{< figure src = "covered_air_intake.JPG" caption = "Covered air intake" width = 400 >}}

Well the only thing that came out of this theory was a stream of diesel straight into my mouth. I had removed the air intake hose and blown some air into it to make sure that there were no blockages. There weren't, and I successfully pressurized the fuel just enough to have it shoot back out of the hose into my mouth and all over my only shirt. Belated apologies to those who had to sit near me on the LIRR.

Finally, I replaced the fuel filter and then very slowly bled the lines from the water separator up to the injection pumps. Still no luck.

## It's the Fuel, Stupid

There's a crucial line in the Beta manual that contained the answer:

>The mechanical fuel lift pump is fitted to all engines as standard, but if a suction head of 0.25m or more is required, then an electric fuel lift pump must be fitted (ask your dealer or Beta Marine).

Basically, the engine is going to struggle to pump fuel if the fuel tank gets too low, since the engine will have to fight gravity harder in pumping the fuel higher. The recommendation in the manual is to install an electric fuel pump if the pumping height is more than 0.25 meters.

My fuel tank is presumably the [AH-20 on this page](https://miraxfuelproducts.com/rectangular-tanks/). That 20 gallon tank is 11-5/8" tall which comes out to 1.72 gallons / inch. 0.25m is 9.84". If we add an extra inch on top of the fuel tank, then in theory the engine will struggle at 2.785" / 4.8 gallons. While this doesn't exactly match my 9.4 gallons that I presumably had left, this seems plausible. 

Based off this theory, I decided to take a shave from Occam's razor and just fill up the tank! Of course, I couldn't actually get off the moring. I bought a 5 gallon jerry jug at West Marine and then rode over to the Manhasset Bay Marina fuel dock. 

{{< figure src = "jerry_jug_bike.JPG" caption = "Riding with a (thankfully) empty jerry jug" width = 400 >}}

I filled up the jug, filled up Peregrine, and the engine started and never stopped. I then took the risk and motored to the fuel dock to fill it up the rest of the way. 

Between the 5 gallon jug, the fuel dock, and a 1-2 gallons from another small tank that I had put into the boat, my fuel tank was at around 8.3 - 9.3 gallons which is right in line with my other estimates.

## The True Test

Sadly, the sailing season ended right around the time I figured all of this out. I decided to keep Peregrine in Jersey City again this year, so a friend and I did the long motor from Jersey City in late October. The engine never sputtered. 

Looks like I need to install an electric fuel pump this winter.
