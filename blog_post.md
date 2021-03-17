# The Ultimate Knife Block

We’ve all been there, chopping vegetables with a knife so blunt it would be more effective to use a teaspoon. In that moment, you reflect on how you got there: your knives were sharp as razors when you bought them but now, three years down the line, they’re thoroughly inadequate. “I should’ve sharpened my knives” you think to yourself. Shoulda, coulda, woulda but I didn’t.

Most of us don’t bother to sharpen our knives. It’s an extra bit of effort and when you’re just trying to make dinner, faffing around with a sharpener is the last thing you want to do. But what if it wasn’t..?

We decided to make a knife block which incorporates a mechanical knife sharpener. A sharpener right next to your knives — and solar powered so you don’t even need to bother charging it! This build is super straightforward and you end up with a great final product which would be a helpful addition to any kitchen!

![](https://cdn-images-1.medium.com/max/2000/1*v4ITmKlkxhz_3udX3dChHg.png)

## Supplies

* Rechargeable 18650 battery — [https://amzn.to/2XF7cno](https://amzn.to/2XF7cno)

* Charge controller TP4056- [https://amzn.to/2XF7cno](https://amzn.to/2L6MU4Y)

* Push button — [https://amzn.to/2XF7cno](https://amzn.to/2GKp5eZ)

* Small motor — [https://amzn.to/2XF7cno](https://amzn.to/2GN44k1)

* Battery Holder — [https://amzn.to/2XF7cno](https://amzn.to/2vwHNAx)

* Glue Gun — [https://amzn.to/2XF7cno](https://amzn.to/2UDKcDz)

* Soldering Iron — [https://amzn.to/2XF7cno](https://amzn.to/2GJ4XtR)

* Wire — [https://amzn.to/2XF7cno](https://amzn.to/2GIzGa9)

* Sharpening stone — [https://amzn.to/2XF7cno](https://amzn.to/2vlYheF)

* 3 packets of spaghetti — [https://amzn.to/2XF7cno](https://amzn.to/2UHnavm)

* Red PLA — [https://amzn.to/2XF7cno](https://amzn.to/2XKszDV)

* Grinding stone — [https://amzn.to/2XF7cno](https://amzn.to/2vlYheF)

* 3X Screws 12mm m3 — [https://amzn.to/2XF7cno](https://amzn.to/2VsZL5g)

## Tutorial 🤖



### Knife Block Design

![](https://cdn-images-1.medium.com/max/2146/1*iUkpLT6kQng8V_bvMCo8Kg.png)

The basic knife block design is a curvy cuboid with a detachable lid and a space for a solar panel in the front. The lid has slots for the knives. To figure out how big the block needed to be and how wide the knife slots would be, we measured the knives we wanted to put in and designed accordingly.

To power the rotating sharpener, we decided to use a solar panel to keep the design cordless (you don’t want to plug *another* thing in the kitchen) and remove the hassle of recharging batteries. Also, chances are that unless you’re a serial knife sharpener, a solar panel will provide plenty power.

The electronics are pretty simple to put together. For power, you need one rechargeable battery — preferably 18650 lithium ion. To charge it, you’ll need a solar panel — we used 5V, 500mA because we had one spare, but a smaller one would be perfectly fine. You’ll also need a battery protection circuit and something to put the battery in.

The whole thing will be controlled by a simple button which sits in the top of the knife block. To operate the sharpener, the button needs to be depressed. This is actually a pretty good safety mechanism because it means the sharpener will stop turning as soon as you let go of the button. On the end of the motor, there’s a small grinding stone which I found online.

### Print the 3D Case

Firstly, 3D print your knife block shell.

We made the 3D design using Fusion360. To be honest, it was quite a fiddly and time consuming process. If you’d like a tutorial on how to do this, please let us know in the comments below. We’re still learning, too, so if anyone has any tips on the design or good places to learn more about 3D design, please share.

### Electronics

We are going to put together following circuit:

![](https://cdn-images-1.medium.com/max/2338/1*PDaujNCcy0wKQ05Pi5G7ZA.png)

### Solder Wires Onto the Solar Panel

Take two wires about 10cm long and solder one onto the positive and one onto the negative tab on the solar panel.

![](https://cdn-images-1.medium.com/max/2144/1*v5D8XdEtbCl_9vw1QpvJnw.png)

## Connect the Battery

Put the battery into the holder and solder the positive and negative wires to the B+ and B- inputs on the charge controller.

![](https://cdn-images-1.medium.com/max/2000/1*J5FcBLTZMxUt62TjQ5m9dQ.png)

## Connect the Switch and Motor

From the push button terminals, solder one wire from the positive output of the charge controller to the input of the push button. Solder another wire from the output of the push button to the positive of the motor. Solder a wire from the negative output of the charge controller to the negative of the battery.

Check the connections work and note which way the motor turns — you want to put it in the case so it will rotate away from you.

![](https://cdn-images-1.medium.com/max/2000/1*-oZbpU8d0jVxaE9VsxeP5Q.png)

![](https://cdn-images-1.medium.com/max/2144/1*qKAPr50UP1R_TbMhsAjTZg.png)

## Put in the Motor

Slot the motor into the hole in the knife block. To reduce vibration and help keep the motor in place, you could glue it using a glue gun — this is optional, though, as it fits snugly.

Push the grinding stone onto the end of the motor.

![](https://cdn-images-1.medium.com/max/2168/1*hLgae61OS7q_1MSZarCrbA.png)

![](https://cdn-images-1.medium.com/max/2150/1*vbggr8Tlf1EjmVYGMV1z9w.png)

## Put on Push Button

Put the push button through the hole in the lid and glue in place.

![](https://cdn-images-1.medium.com/max/2114/1*nqT90IR4rF0zLL2MykEz0g.png)

## Put on the Solar Panel

Solder the positive wire from the solar panel to the positive input on the charge controller. Solder the negative wire from the solar panel to the negative input on the charge controller.

Glue around the perimeter of the case and push on the solar panel.

![](https://cdn-images-1.medium.com/max/2084/1*J3a60hdIQPgy-IadGzFpuQ.png)

![](https://cdn-images-1.medium.com/max/2128/1*RIgL4a6sBKm5sng0GnwNDw.png)

## Fill Up With Spaghetti

Fill the large internal cavity with spaghetti. This might sound random, but it gives the block some weight so it doesn’t move around when sharpening and it also helps keep the knives in place.

We used about 3 packs of spaghetti to fill the space. It was a bit long so we trimmed the ends so the lid would fit.

![](https://cdn-images-1.medium.com/max/2166/1*cMpFwdorFv6tm9FL1HS1sw.png)

## Put on Lid

Screw the lid in place to close the knife block.

![](https://cdn-images-1.medium.com/max/2000/1*jqaOpfrAAaO36alXhyHscA.png)

## Put in Knives

Put your knives into your block and swirl it round in the sun.

We did think that adding little rubber feet would be a good way to reduce vibration, noise and slipperiness, but we didn’t quite get round to that. We also thought that we could add a bottle opener or an electric can opener to make this the ultimate kitchen gadget!

If you have any suggestions for improvements or additions, please let us know in the comments below!

![](https://cdn-images-1.medium.com/max/2140/1*Krv2qVSGo7C49A1YELRYag.png)

## Thanks for reading

I hope you have enjoyed this article. If you like the style, check out [T3chFlicks.org](https://t3chflicks.org/) for more tech focused educational content ([YouTube](https://www.youtube.com/channel/UC0eSD-tdiJMI5GQTkMmZ-6w), [Instagram](https://www.instagram.com/t3chflicks/), [Facebook](https://www.facebook.com/t3chflicks), [Twitter](https://twitter.com/t3chflicks)).