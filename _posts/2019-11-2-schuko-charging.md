---
layout: post
title: The Schuko Charging
---

The name [Schuko](https://en.wikipedia.org/wiki/Schuko) comes from german Schutzkontakt, and is a typical Europe household electric
plug. The easiest way to charge your car at home is from a Schuko. However it may not be possible
in certain dwellings:

* If the parking lot is far from the house
* Or if there is a road between your house and the parking lot.

If anything of the above applies, then you're out of luck, since you can't draw an extension cord easily from your Schuko
to your car parking spot.

## The Limits of Schuko-Charging

EVs use more electricity than any other electric appliance in your home *by far*. To fill in that 22kWh battery,
you would need to charge 6-7 hours at the speed of 3,5kW. Compare that to your electric grill which draws 2kW for maybe 1 hour;
an electric heater which draws 1,5kW for perhaps 3-4 hours tops. The only comparable device is sauna, but we'll get there in a minute.
The bottom line is that the act of charging of your car at home (or when being over at friends' or family visit) will stress the
electric wiring and will near its limits, therefore it's important to know what those limits are.

The Schuko was designed to allow draw the maximum of 16A at 220V (3,5kW), but *ONLY FOR 2 HOURS*. That is usually quite enough for all
of typical household appliances (except for sauna, but sauna is hardwired directly to cables, not connected via Schuko),
however that's not nearly enough to charge an electric car. Charging at 16A at 220V for 2 hours will charge your
battery for 6,6kWh only, which is roughly 50km of range. Not to mention that you shouldn't load the fuse on 100%,
but only at 80%, which means charging at 13A max on a 16A fuse, or 8A on a 10A fuse.

To sum up: you can charge at 13A from Schuko as long as you want, but ONLY IF ALL of the following is met:

1. You know for sure that the fuse is 16A,
2. The building has been built in the year 2000 at the latest (so that the wiring is good),
3. Your extension cord (jatkojohto) can handle 13A continuous draw.

If anything of the above is not met, charge at 10A (or even 8A to be extra sure, or in case of 10A fuse).

In order to charge at 13A or 10A or 8A, you need two things:

* A proper extension cord,
* A car charger with configurable charging speed.

## Extension Cords (Jatkojohdot)

Buy a proper outside extension cord, at least IP44-rated (see [Wikipedia waterproof IP rating](https://en.wikipedia.org/wiki/IP_Code)
for more details). For 8A charging this should be enough:
[Gelia jatkojohto 1-osainen 10 m H05RR-F 3x1.5 IP44](https://www.kodinterra.fi/fi/terra/gelia-jatkojohto-1-osainen-10-m-h05rr-f-3x15-ip44-punainen).
For 13A charging make sure to buy an extension cord with a wire diameter of 2.5mm. Bigger wire diameter mean
less resistance, which means less heat and less power losses, and you definitely don't want your extension cord to overheat.
For example this one: [Gelia jatkojohto 1-osainen 15 m H07RN-F 3x2.5 IP44](https://www.kodinterra.fi/fi/terra/gelia-jatkojohto-1-osainen-15-m-h07rn-f-3x25-ip44).

Beware: don't buy the cable that can be rolled, e.g. [Gelia kaapelikela anti-twist 25m 3x1,5](https://www.kodinterra.fi/fi/terra/gelia-kaapelikela-anti-twist-25m-3x15).
When rolled, such cable can only transfer 1kW, which is 4,5A at 220V, and I don't know of any car/charger which can charge at such a low speed (with the exception of Tesla).
To be extra safe, unroll your extension cord when charging.

To be extra sure, you can also buy a protector which shields your charger-to-extension-cord connection point:
[SUOJAKOTELO OPAL JATKOJOHTOON VEDENKESTÄVÄ](https://www.k-rauta.fi/rautakauppa/s%C3%A4hk%C3%B6--valaistus-ja-turvallisuus/sahkotarvikkeet/jatkojohdot-ja-kelat/suojakotelo-opal-jatkojohtoon-vedenkest%C3%A4v%C3%A4-5306926).
However, not all extension cords and car chargers fits within the protector; also if the extension cord ending is not straight it will not fit.

## Car Chargers

The only original car charger I know of which doesn't charge at 16A is Tesla UMC (Universal Mobility Connector) charger:
if plugged into Schuko it will automatically limit itself to 13A, and you can further lower the charging speed from the car itself to any value below 13A.

If you don't own a Tesla then you'll need to buy a separate car charger. The only car chargers that I found which allow for configurable 13A/12A/10A/8A
charging speeds are made in China. This one worked for me really well: the [Zencar Type 1 Schuko Charger](https://www.aliexpress.com/item/32807932284.html):

1. It allows for 8A and 12A charging speed (even though 12A charging speed is not listed on the page, it is still supported by the charger)
2. It has a Schuko connector with a straight cable, which can be used with the suojakotelo thing as listed above.
3. I have Nissan Leaf, therefore Type 1 charger. If you have any other car, Type 2 is probably for you - check first before ordering!
4. It has all sorts of protection and CE sticker.

> There are no CHAdeMO nor CCS portable car. Only Type 1 and Type 2 ones.

However, generally any charger with the CE sticker and 8A+12A charging speed support will work nicely. Just search the [AliExpress](https://www.aliexpress.com)
site - you'll find lots of those chargers at very friendly prices.

## General Tips

1. Make sure that the charger-to-extension-cord connection point is not just lying on the ground.
   Even when protected with Suojakotelo, it won't work when submerged in water.
2. You should attach the cables to the wall with [ruuvikiinnike](https://www.k-rauta.fi/rautakauppa/ruuvikiinnike-thorsman-tcs-c3-10-14-v-100kpl). That way,
  the cables won't simply lie around for you to kick them away. Also they will support the extension cord so that it won't simply hang with its entire weight on the Schuko
  plug and won't create mechanical stress on the Schuko plug.
3. You can screw the car charger to the wall as well; then you can either hang the charging cable on one or two [seinakoukku](https://www.biltema.fi/tyokalut/tyokalujen-sailyttaminen/tyokalupitimet/seinakoukku-2000023075)
   hooks attached to a wall, or around a Car Heater Plug Box.
4. When charging for the first time: after 2 hours of charging check all three connection points with your bare hand that everything is cool.
   Make sure to check all three connection points: the extension cord-to-schuko, the schuko plug itself, and the charger-to-extension-cord.
   If they are clearly warm, stop the charging immediately and replace them.

## Conclusion

This particular setup worked for me really well. I used to live in an older house; the Schuko plug was protected by a 10A fuse and the wiring was
probably older, that's why I charged at 8A. I used 20meter extension cord with the diameter of 1,5mm protected by suojakotelo, and charged using the Zencar
charger at 8A (The Zencar charger arrived in 2 weeks from China to Finland). Even though the fuse box was the old type with
screwable fuses (charging on such fuses is explicitly banned in the Nissan Leaf manual :-) ), the setup worked flawlessly during my entire stay (1 year).
Then I moved to another house with a car heater plug box and a 16A fuse, and so another round of experimenting began.
But more about that in the next blog.

