---
layout: post
title: Home-Charging Electric Vehicle in Finland - Basics
---

One day I decided to hop on the EV revolution and got myself an used Nissan Leaf. The price
was decent, and so I thought it could be an excellent testing grounds for me to evaluate whether
I'm ready to fully switch to EVs.

After I bought the car, I realized to my horror that the range is only 160km (which means daily charging),
and it lacked fast-charging (which ruled out charging in a shopping mall since slow-charging would take at least 5 hours).
So home charging was the only option, but I knew nothing about the possibilities and dangers of home charging.
I got terrified that I wouldn't be able to charge the car (or I'd burn my house in attempt to do so at home),
the fuses would constantly trip because of the enormous electricity draw,
and I thought even about selling the car and going back to gasoline.

Ultimately I didn't, but having a blog like this would have helped me tremendously at that time.
That's why I decided to write down all of my knowledge and experience.

## The Theory, The Range, The Money

First, a couple of theory. The most basic thing is kilowatt and kilowatt-hour:

* Kilowatt measures speed of charging: the speed of electric power transfer to a battery
* Kilowatthour measures accumulated energy; it also measures the maximum capacity of a battery.

The math is simple: if you charge at a speed of 2kW, then after 10 hours your battery will gain 2kW * 10h = 20kWh.

> A bit of a stupid parable: Think driving at 50km/h for 10 hours, you'll get as far as 50 km/h * 10h = 500km.

An efficient EV such as Tesla Model 3 or Nissan Leaf will use 13kWh per 100km. The Leaf has around 22kWh of usable battery,
which yields range of 100*22/13=~169km; Model 3 has 50kWh battery which thus yields range of roughly 384km.

The price of (fully renewable hydro) home electricity in Finland in 2019 is roughly 0,14 EUR per kWh; that means
that by charging at home you'll pay 1,82 (13kWh * 0,14) EUR to drive 100km, as opposed to 10 EUR per 100km when driving
on gasoline. The savings are huge.

How fast can you charge at home? That's really easy to compute, since you simply multiply volts by ampeurs to get kW.
From a regular household outlet (called Schuko) which is 220V 16A you'll get at most 220*16=3520W=3,5kW charging speed.
In practice the charging speed is smaller, but that's something we'll discuss in another blog post.

## The Charging Socket Types: Quick Overview

There are four types of sockets for charging your car. The first one is [Type 1/SAE J1772](https://en.wikipedia.org/wiki/IEC_62196)
socket, used by Nissan only; another is [CHAdeMO](https://en.wikipedia.org/wiki/CHAdeMO) which is again used by Nissan only.
So, if you don't plan to buy Nissan, then you can forget about these two plug types altogether.

By default in Europe all charger stations and all cars use [Type 2 Mennekes](https://en.wikipedia.org/wiki/IEC_62196) connector and
its [Combined Charging System or CCS](https://en.wikipedia.org/wiki/Combined_Charging_System) extension which allows high charging speeds
(up to 350kW, but usually the car will allow much smaller speeds, typically around 100kW). Typically EV will
have just the CCS plug, which can charge both from the CCS and Type 2. Type 2 chargers often lack the cable (so-called untethered),
therefore it's a good idea to have the Type2-Type2 cable in your car all the time.

## Where To Charge Your Car

I see the following options to charge your car:

### Charging Once Per Week At a Quick-Charger

If you have a car with a large battery which has the capability to quick-charge (e.g. Tesla Model 3),
you can simply quick-charge once per week, for example
in the K-CityMarket from the K-Lataus quick charger, as you do shopping.

K-Lataus supports 50kW charging speed, so it's one of the slower charging stations
(compared to Tesla's Supercharger network with 150/250kW speed or IONITY's 350kW speed; however typical car can only charge at 100kW speed tops anyway).

Fast-charging is a bit more expensive. For example with K-Lataus you pay 0,2 EUR per minute of charging;
in order to charge 50kWh you'll need to charge for an hour or more. That means ~3 EUR for 100km range, which is still a very decent price.

> The speed of charging decreases to roughly 25kW when the battery is ~85%+ full (depending on the car).
That's why it's even more expensive to fast-charge to 100%, simply because you still pay per minute but you only get ~25kW of charge. That's why
people typically fast-charge only until 80%.

However, fast-charge doesn't work with a cheap Leaf or with a car which can't quick-charge. Before buying a car,
make sure that it either has CCS or CHAdeMO plug, or else don't drive outside of the city with the car.

Fast-charging is an excellent
option for city dwellers which typically live in a block of flats and often has no other possibility to charge.

### Charging At Home From a Wall Charger

Safest option, however not the cheapest one. Before shopping, remember that
the wall charger either needs to have a RCD/RCCB fuse integrated, otherwise
you'll need to pay an electrician to purchase one for you (200-300 EUR).

The cheapest wall charger is [Webasto Pure](https://www.finnparttia.fi/WEBASTO-16-latausasema)
which goes for 650 EUR and contains the RCD/RCCB fuse integrated.
The Tesla Wall charger is cheaper at 500 EUR but it has no RCD/RCCB fuse built-in.
On top of that you need to pay roughly 500 EUR for a certified electrician to install the charger properly.

The Wall Charger is very safe since it's connected directly to the wires. A friend of mine used to charge from Schuko until he found the Schuko
plug one day completely black, as it heated up because of fast electricity draw and started to burn (even though there were no flames).
However, he charged at 16A which is a big no-no with Schuko, as you will learn in the next blog.

Wall Charger provides alternating current (AC) and can usually charge at 3,3kW (16A at 220V), which is about 25km of range per hour.
Higher speeds are possible: 6,6kW, 11kW or even 22kW. All cars can handle 6,6kW, however not every car can handle 11kW, and only a few
cars can handle 22kW AC. For example Tesla Model 3 can handle only 11kW AC, even though it can handle 170kW-250kW DC.
The problem is that the battery charges with DC and thus the car needs an on-board AC->DC converter.
More powerful converters are more expensive, bigger and heavier.

Wall Chargers however may not make much sense for a small house. At 6,6kW speed (32A at 220V) you'll need a special 40A fuse or a
3-phase plug, which is very expensive to install. Since
typical Finnish house is connected to the mains with 3-phases * 25A fuse per each phase,
charging with 1-phase 32A 220V is not possible since the fuse can only handle 25A and would trip; not to mention
that there are other appliances connected to that phase as well.

Therefore, the safest speed is 3,3kW (or 5,2kW when 3-phase is used; then the charger would
use 3 x 8A x 220V which leaves 25A-8A=17A for other appliances, should be more than enough).
You need to decide whether you want to pay ~1000-1500 EUR for increased charging speed
and safety, or achieve cheaply 1,7kW charging speed (about 10km of range per hour gained)
with the mobile charger and Schuko. At first I went with the Schuko option,
but now I'm toying with the idea of having a proper charger installed; see
[Home Charging in Finland - Revisited](../home-charging-finland-revisited/)
for more details.

### Charging From The Car Heater Plug Box

This is the most intriguing option since the Heater Plug Box provides Schuko with all the cabling and the fuses already installed.
So, it's just plug and charge, right? Well, not entirely:

* The electricity metering in a parking lot/garage block could be shared for the entire neighbourhood (unless you have the heater box stuck to your house).
That means that your neighbours will pay for your charging, and they aren't going to like you and your EV car.
* The car box always turns off after 2 hours. It is possible to modify this, but definitely not on a shared car heater box.
* The Schuko plug in the car heater box will mechanically suffer if you simply hang the mobile charger with its entire weight on the Schuko plug.

However, this is a very viable option if you live in a house which you own, and you are therefore free to modify the Heater Plug Box a bit.
I'll explain how to do that in next blog.

Also, often it is possible to get a deal with the housing company, to pay
around 30 EUR per month (the money is negotiable) for unlimited charging from
the heater box.

### Charging From a Schuko Overnight

This is usually the easiest and cheapest option since no electrical wiring needs to be installed. Detached, semi-detached and
row houses tend to have at least one or two Schuko plugs on the outside wall or in your garage,
connected to your fuse box and to your electricity meter.
If it is possible to draw an electric cable to your parking lot, then you can simply plug in your mobile charger and
charge. However, you need to take precautions:

* You need to protect the connectors from the weather, namely from the snow and rain. You can't simply leave the connectors lie on the ground in a
  puddle of water - it will short the circuit and trip the fuse at the minimum, regardless of the IP waterproof protection rating.
* You need to make sure there are no other appliances connected to the same circuit, otherwise you can trip the fuse.
* If the schuko plug or the internal wiring is old, charging too fast can make the schuko burn and break.
  However, don't worry - we will discuss how to charge responsibly in the next blog.

Since you usually charge overnight, you usually can leave the car plugged in and charging for 12 hours straight; even with the
safest and slowest charging that should give you enough juice:

* Charging at 6A (1,3kW) will give you 10km per hour, or 120km per 12 hours;
* Charging at 8A (1,76kW) will give you 13km per hour, or 160km per 12 hours (fully charges a 2015 Leaf with 24kW battery)
* Charging at 10A (2,2kW) will give you 17km per hour, or 200km per 12 hours
* Charging at 13A (2,9kW) will give you 20km per hour, or 260km per 12 hours

### RCD/RCCB Fuse when charging from Schuko

A residual-current device (RCD), or residual-current circuit breaker (RCCB) or Earth Leakage Circuit Breaker or Safety Switch, is
a device that quickly breaks an electrical circuit to prevent serious harm from
an ongoing electric shock. Its purpose is to prevent you from getting a fatal electric shock if
you touch live part, such as a bare copper wire under high voltage.  

It is important to be protected with the RCCB fuse. Usually the fuse is in the fuse box, see image below.
In such case the charger itself doesn't need to contain the RCCB fuse. However, in older
houses there is no RCCB fuse and then it's important to buy a charger with the RCCB fuse
built-in. Tesla UMC chargers does *not* contain RCCB fuse.

![RCCB fuse in a fuse box]({{ site.baseurl }}/images/2019-11-1/rccb.jpg)

For example I've found this nifty charger which comes with the RCCB fuse:
[Metron PC03](https://eauto.si/metron-shop/product/type2-schuko-cee-16a-1-phase/).

There are two types of fuses, [RCD A and RCD B](http://www.electrical-installation.org/enwiki/Types_of_RCDs). RCD A guards against AC only, RCD B
guards against AC and DC as well. Some chargers are protected by RCD A while others are protected by RCD B.

Since it's good to have extra protection, I'll buy the Metron PC03 with the RCD A fuse,
to charge when on the road.

### Charging From The blue "Caravan" plug or the red 3-phase plug

If your house has the [blue "caravan" plug](https://www.amazon.co.uk/240V-Socket-Caravan-Motorhome-Cable/dp/B076GBH4XQ)
or the [red 3-phase plug](https://en.wikipedia.org/wiki/IEC_60309) (this is very rare),
then you can charge full-speed 16A/220V from the blue plug, since they were made to withstand 16A for 6 hours.
It is possible to buy such chargers cheaply, for example on AliExpress; just make sure they are meant for European market
and are marked with CE. I'll post the links in the next blog.

### Conclusion

Since I was living in a rented semi-detached house at that time, with shared car heater boxes, that ruled out the car heater box charging.
My Nissan Leaf couldn't fast-charge, which ruled out quick-charger. The house wasn't mine and I did not want to drill any holes for a wall charger,
which ruled out a wall charger. The only option was therefore an outside Schuko.

The house was old-ish (built in the 80ties probably), which meant old fuses (the ones that you
[screw in, so called DIAZED fuses](https://en.wikipedia.org/wiki/IEC_60269)) and probably old wiring.
Charging full speed at 16A sounded like a recipe for disaster. I had to think of something.

*However, if only the fast charger option works for you, then don't buy the cheapest Leaf*.
You absolutely need a car that can fast-change at decent speed on a fast charger.

## More Info

* [STEK: Miten ja missä sähköauto ladataan](https://stek.fi/energiatehokkuutta-sahkolla/sahkoautoilu)
