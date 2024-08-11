---
layout: post
title: Nissan Leaf 2022 - general maintenance
---

This article shows tips for maintenance of various car parts: replacing windshield
wipers, spare lug nuts, how to jack the car, etc.

## Spare wheel lug nuts

TODO revisit. Leaf 2022 uses 21-socket-size nuts, but no idea otherwise.

Nissan Leaf 2015 uses M12 1,25 lug nuts; you can buy spare for example from
Biltema: [Wheel Nut Kit M12 x 1,25, 35mm, Art. 33-3305](https://www.biltema.fi/en-fi/car---mc/styling/exterior-styling/wheel-nuts-10-pcs-2000019355).

## Tightening the lug nuts

The tightening torque is 108 NM; I recommend getting a proper torque spanner
such as [Momenttiavain 70-350 NM](https://www.biltema.fi/tyokalut/kasityokalut/hylsytyokalut/momenttiavaimet/momenttiavain-70-350-nm-2000030634).
The socket size is 21".

## Jacking

Nissan Leaf's underbody is not flat but instead there is a pinch rail or
a pinch weld; this [nissan leaf jack video](https://www.youtube.com/watch?v=abbDGR60NsE)
contains more information.

What's totally weird is that I've failed to buy pinch rail jack adapter in Finland.
The Nissan dealership, Motonet and also Fixus simply told me that it's not being
sold in Finland, and that I should simply jack the car and risk twisting of the pinch rail.
Probably everyone simply uses a hockey puck or similar. The best thing
might be to order a pinch rail jack adapter from AliExpress or Amazon and have
it delivered to Finland, but that could be rather expensive.

I tried to order something from AliExpress, but the rubber is not strong enough:
it twists and bends almost to the point of the car falling off the jack stand.

I ultimately purchased [Biltema's Jack Pad](https://www.biltema.fi/autoilu---mp/korjaamovarusteet/nostotyokalut/tunkit/jack-pad-2000017051)
and a couple of hockey pucks - looks to be working the best.

## Tyres

P205/55 R16

## Windshield wiper replacement

* Rear windshield wiper: 350mm; I bought [BOSCH Twin Rear H 354 at Autodoc](https://www.autodoc.fi/bosch/1194143);
  for replacement tutorial see the [Nissan Windshield replacement video](https://www.youtube.com/watch?v=lTsL6_ILutM)
* Front windshield wipers:
   * Driver's side: 650mm/26" Hybrid; I bought [Bosch AeroTwin Retrofit AR26U/AR650U in Motonet](https://www.motonet.fi/fi/tuote/120192/Bosch-AeroTwin-RetroFit-AR26U--AR650U-tuulilasinpyyhin-65-cm)
   * Passenger: 400mm/16" Hybrid; I bought [Bosch AeroTwin RetroFit AR 16 U / AR 400 U in Motonet](https://www.motonet.fi/fi/tuote/120184/Bosch-AeroTwin-RetroFit-AR16U--AR400U-tuulilasinpyyhin-40-cm).
     The page also links to a video showing how to replace the wiper.
   * You can also buy both wipers as a pair: [Bosch AeroTwin Retro AR653S at Autodoc](https://www.autodoc.fi/bosch/1194314).

I've discovered the wiper exact part types via [Bosch Wiper Blade finder](https://www.boschwiperblades.com/)
which will find AR26U and AR16U exactly as above. You need to put Nissan Leaf 2018.

* The AR stands for "AEROTWIN Upgrade" whatever that is,
* The U stands probably for Hybrid, or god knows what.

## 12V battery

Check out this [youtube video on replacing the 12v battery in nissan leaf 2014](https://www.youtube.com/watch?v=sS3ssRpJYdg),
and also [Why 12-Volt Batteries in Electric Cars Get Sick](https://www.youtube.com/watch?v=pu30bchGu50).

Nissan Leaf 2022 battery group is 12V - L1 50Ah 420A (EN) MF; the dimensions should be 204 x 170 x 190 mm; the terminal connector diameter is 17mm. Make sure to pay attention to R which says that
the positive terminal is to the **right**. (measured on my leaf: W=170mm, L=204mm, H=190mm, height including the terminal connectors = 190mm).

In Finland here are proper replacements for the battery:

* [Exide EA530 53 Ah / 540 A akku P207 x L175 x K190 -+](https://www.motonet.fi/tuote/exide-ea530-53-ah-540-a-akku-p207-x-l175-x-k190?product=90-01738)
* [Exide EB500 50 Ah / 450 A akku P207 x L175 x K190 -+](https://www.motonet.fi/tuote/exide-eb500-50-ah-450-a-akku-p207-x-l175-x-k190?product=90-9505)
* [Exide EL550 55 Ah / 540 A akku P207xL175xK190 -+](https://www.motonet.fi/tuote/exide-el550-55-ah-540-a-akku-p207xl175xk190?product=90-01897)
* [MTX Energy Käynnistysakku 52Ah/470A P207xL175xK190 -+](https://www.motonet.fi/tuote/mtx-energy-kaynnistysakku-52ah470a-p207xl175xk190?product=90-01421)

I have no first-hand experience with a replacement yet.

### 12V Battery Charging

The following applies to Leaf 2014 only; I have no idea whether this applies still to Leaf 2022. I'll update when I figure this out.

Beware: Nissan Leaf only charges its 12V battery when:
* It's powered on and there's 14V coming from the traction battery,
* Or when the traction battery is being charged.

Therefore, the 12V battery will NOT be charged when Leaf is:
* powered off with charging cable unplugged, or
* Leaf is done charging and is not charging anymore (e.g. after it charged its main traction battery to 100%)

Therefore, when you leave your Leaf charging for a month in a cold weather,
it's possible to find the car with a dead 12V battery even though Leaf was connected
to the charger for the whole time.

## Dimensions

* Length: 4479 mm
* Width: 1790 mm
* Height: 1535 mm (with 16" wheels)
* Wheelbase: 2700 mm
* Ground clearance: 150 mm

## Spare Air cabin filter

Dimensions: 260mm x 150mm x 25mm; Suodatin or Raitisilmasuodatin

E.g. [CORTECO 80001720](https://www.autodoc.fi/corteco/2103771) or [BOSCH](https://www.autodoc.fi/bosch/7448896).

## Flaws

Fatal flaw preventing any long-distance travels: Leaf doesn't have active cooling of its battery;
fast-charging 2 or more times per day [makes the the battery critically warm](https://www.youtube.com/watch?v=L1Wf04npzMw).
Slow-charging via the Type 1 AC connector is okay.

Another flaw is that the water from the windshield [drains onto a suspension strut](https://www.youtube.com/watch?v=IaTP5wfawTw),
causing it to rust. I tried ordering [Front Suspension Strut Top Mount Cover for Nissan Leaf ZE0](https://www.aliexpress.com/item/1005006439525971.html) -
even though it's intended for the older generation of Leafs, hopefully it will match the new ones as well. I'll let you know.
