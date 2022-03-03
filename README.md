# Toshiba-T1900

# Interesting features

- Trackball connector/interface

# Hard drive

- CP-2124 Conner 120MB 2.5-Inch 17mm IDE Notebook Hard Drive

![image](https://user-images.githubusercontent.com/38451588/156491386-d5c623de-c9ef-4468-9539-4d9eb9a41c10.png)


# Unverified/unsorted info

When the laptop is running from the AC adaptor, you press the switch to turn it on. After only a few seconds, it shuts itself off. The DC IN light may flash. If the laptop has a status LCD, it may display a P30 or P31 error.


If your laptop still runs off the battery without the adaptor plugged in, one solution is to just run off the battery, but that is rather inconvenient. To run the laptop off the adaptor requires you to replace a capacitor inside the laptop. I found opening up the laptop and then reassembling it to be difficult. All the parts are so physically integrated it's like a puzzle. First you have to remove the plastic piece surrounding the keyboard. To do so, first remove all the screws you can find. Then you need to unsnap the keyboard surround from the base. I used a very small, thin screwdriver (a knife might work well) to work around the seam and unsnap the keyboard surround from the lower half. I have only worked with the T1900C, so there may be differences from your model. Next you need to gain access to the power supply area, which in most if not all models is probably located near the DC IN jack. There will be a few large electrolytic capacitors in this area. You will probably have to remove the keyboard and several metal shields. In the T1900C it was necessary to remove the entire circuit board assembly and take it completely apart so I had the lower system board by itself.

Now you need to locate the bad capacitor. In a message on Computing.Net, a person with a T4600 reports replacing a 1000uF 6.3 volt capacitor. In the T1900C I found just such a capacitor, 1000uF 6.3VDC and after replacing it, the laptop works. It sounds like a similar power supply design was used in many models, so look for a capacitor with these specifications.

Once you have found the capacitor to replace, you need to remove the old one. For some reason it was extremely difficult for me to desolder the capacitor and I ended up just pulling the capacitor body off the leads and then removing the leads individually. After I removed the leads, the holes in the circuit board were filled with solder which I was able to remove using a desoldering braid.

Now you need to get a replacement capacitor. The physical dimensions of the replacement will be very important, so you'll need to measure how big of a capacitor you can fit in your model. Since the original capacitor failed, the circuit apparently stresses this component, so it is probably a good idea to get a capacitor made for durability, with high permissible ripple current / low ESR. I used a 1000uF 6.3VDC Elna capacitor which I bought from Mouser (item 555-6.3V1000). It was 2cm tall and 8mm in diameter, with 3mm lead spacing, but I managed to fit it in. However, it was a difficult fit, so you may want to look at other capacitors if you don't think this one would fit in your model. I also recommend getting some replacement fuses in case you blow some of them. Somehow I managed to blow a 5 amp fuse on the lower board which connects to the battery. Later in my experimenting I managed to blow both 2 amp fuses on the upper system board. I replaced the 5 amp SMD fuses with Mouser part 5762-451005. They have 2 amp fuses also, part 5762-451002. Some models may require different fuses. You can look for them on the circuit boards. The fuses should have the current rating printed on the body, like 5A or 2A.


https://vobarian.com/toshibaProblem.html



