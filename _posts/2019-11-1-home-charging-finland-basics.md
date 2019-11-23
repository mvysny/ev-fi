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
the fuses would constantly blow because of the enormous electricity draw,
and I thought even about selling the car and going back to gasoline.

Ultimately I didn't, but having a blog like this would help me tremendously at that time.
That's why I decided to write down all of my knowledge and experience.

## The Theory, The Range, The Money

First, a couple of theory. The most basic thing is kilowatt and kilowatt-hour:

* Kilowatt measures speed of charging, speed of electric power transfer to a battery;
* Kilowatthour measures the capacity of a battery.

The math is simple: if you charge at speed of 2kW, then after 10 hours your battery will gain 2kW * 10h = 20kwh.

> A bit of a stupid parrable: Think driving at 50km/h for 10 hours, you'll get as far as 50 km/h * 10h = 500km.

An efficient EV such as Tesla Model 3 or Nissan Leaf will use 13kWh per 100km. The Leaf has around 22kWh of usable battery,
which yields range of 100*22/13=~169km; Model 3 has 49kWh battery which thus yields range of roughly 377km.

The price of (fully renewable hydro) home electricity in Finland in 2019 is roughly 0,14 EUR per kWh; that means
that by charging at home you'll pay 1,82 (13kWh * 0,14) EUR to drive 100km, as opposed to 10 EUR per 100km when driving
on gasoline. The savings are huge.

How fast can you charge at home? That's really easy to compute, since you simply multiply volts by ampeurs to get kW; so
from a regular household outlet (called Schuko) which is 220V 16A you'll get 220*16=3520W=3,5kW charging speed.

## The Charging Socket Types: Quick Overview

There are the following types of sockets for charging your car. The first one is [Type 1/SAE J1772](https://en.wikipedia.org/wiki/IEC_62196)
socket, used by Nissan only; another is [CHAdeMO](https://en.wikipedia.org/wiki/CHAdeMO) which is used by Nissan only.
So if you don't plan to buy Nissan, then you can forget about these two plugs altogether.

By default in Europe all charger stations and all cars use [Type 2 Mennekes](https://en.wikipedia.org/wiki/IEC_62196) connector and
the [Combined Charging System or CCS](https://en.wikipedia.org/wiki/Combined_Charging_System) extension which allows high charging speeds.

## Where To Charge Your Car

There are generally three options to charge your car:

### Charging Once Per Week At a Quick-Charger

If you have a car with a large battery which has the capability to quick-charge (e.g. Tesla Model 3),
you can simply quick-charge once per week, for example
in the K-CityMarket from the K-Lataus quick charger, as you shop.

K-Lataus supports 50kW charging speed, so it's not that quick
(compared to Tesla's 150/250kW speed or IONITY's 350kW speed; however typical car can only charge at 100kW speed tops anyway).

This is a bit more expensive: you pay 0,2 EUR per minute of charging; in order to charge 50kWh you'll need to charge for an hour.
Or even more than a hour: the speed of charging decreases to roughly 25kW when the battery is 85%+ full. Regardless,
that means 12 EUR for ~400km range, which is still decent
price.

However, this option doesn't work if you only have Leaf, or a car which can't quick-charge. Yet, this is an excellent
option for a city dwellers with no possibility to charge by other means.

### Charging At Home From a Wall Charger

Safest option, however not the cheapest one.
You need to pay 650 EUR for the cheapest wall charger (currently Webasto; Tesla Wall charger is cheaper at 500 EUR but it requires
some kind of a DC leakage protection fuse which costs around 200-300EUR) and 500 EUR for an electrician to install it properly.

However, it's safest since it's properly installed. A friend of mine used to charge from Schuko until he found the Schuko
plug one day completely black, as it heated up because of the electricity draw and started to burn (even though there were no flames).
Yet, it's easy to avoid this, just read on.

Wall Charger provides alternating current (AC) and can usually charge at 3,3kW (16A at 220V), which is about 25km of range per hour.
Higher speeds are possible: 6,6kW, 11kW or even 22kW. All cars can handle 6,6kW, however not every car can handle 11kW, and only a few
cars can handle 22kW AC. For example Tesla Model 3 can handle only 11kW AC, even though it can handle 170kW-250kW DC.
The problem is that the car needs an on-board AC->DC converter, and more powerful converters are more expensive.

Also, for 6,6kW speed (32A, 220V) you'd need a special 40A fuse or a 3-phase plug, which is very expensive to install. Since
typical Finnish house is connected to the mains with 3-phases * 25A fuse per each phase,
charging with 1-phase 32A 220V is not possible since the fuse can only handle 25A and would blow up; not to mention
that there are other applicances connected to that phase as well.

Therefore, the safest speed is 3,3kW. Since you can easily and cheaply achieve 2,6kW charging speed (about 20km of range per hour gained)
with the mobile charger and Schuko, I went with the Schuko option.

### Charging From The Car Heater Plug Box

This is the most intriguing option since the Heater Plug Box provides a Schuko with all the cabling and the fuses.
So, it's just plug and charge, right? Well, not entirely:

* The electricity metering in a parking lot/garage block is shared for the entire neighbourhood (unless you have the heater box stuck to your house).
That means that your neighbours will pay for your charging, and they aren't going to like you and your EV car.
* The car box always turns off after 2 hours. It is possible to modify this, but definitely not on a shared car heater box.
* The Schuko plug in the car heater box will mechanically suffer if you simply hang the mobile charger with its entire weight on the Schuko plug.

However, this is a very viable option if you live in a house which you own, and you can modify the Heater Box a bit.
I'll explain how to do that in next blog.

### Charging From an Outside Schuko Overnight

This is usually the easiest and cheapest option since no electrical wiring needs to be installed. Detached, semi-detached and
row houses tend to have at least one or two Schuko plugs on the outside wall, connected to your fuse box and to your meter.
If it is possible to draw an electric cable to your parking lot, then you can simply plug in your mobile charger and
charge. However, you need to take precautions:

* You need to protect the connections from the weather - from the snow and rain. You can't simply leave the connection lie on the ground in a
  puddle of water - it will short the circuit and blow the fuse at the minimum, regardless of the IP protection rating.
* You need to make sure there are no other appliances connected to the same circuit, otherwise you can blow up the fuse.
* If the schuko plug or the internal wiring is old, charging too fast can make the schuko burn and break.
  However, don't worry - we will discuss how to charge responsibly in the next blog.

Since you usually charge overnight, you usually can leave the car plugged in and charging for 12 hours straight; even with the
safest and slowest charging that should give you enough juice for 120km. 

### Charging From The blue "Caravan" plug or the red 3-phase plug

If your house has the [blue "caravan" plug](https://www.amazon.co.uk/240V-Socket-Caravan-Motorhome-Cable/dp/B076GBH4XQ)
or the [red 3-phase plug](https://en.wikipedia.org/wiki/IEC_60309) (this is very rare),
then you can charge full-speed 16A/220V from the blue plug, since they were made to withstand 16A for 6 hours.
It is possible to buy such chargers cheaply, for example on AliExpress; just make sure they are meant for European market
and are marked with CE.

### Conclusion

Since I was living in a rented semi-detached house at that time, with shared car heater boxes, that ruled out the car heater box charging.
My Nissan Leaf couldn't fast-charge, which ruled out quick-charger. The house was not mine and I did not want to drill any holes for a wall charger,
which ruled out a wall charger. The only option was therefore an outside Schuko.

The house was old-ish (built in the 80ties probably), which meant old fuses (the ones that you
[screw in, so called DIAZED fuses](https://en.wikipedia.org/wiki/IEC_60269)) and probably old wiring.
Charging full speed sounded like a recipe for disaster. I had to think of something.

*However, if none of these options work for you, then don't buy the cheapest Leaf*. You absolutely need a car that can fast-change
at decent speed on a fast charger.

