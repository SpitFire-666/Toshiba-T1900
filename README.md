# Toshiba-T1900

# Interesting features

- Trackball connector/interface
- Pop-out feet

# Trackball

![image](https://user-images.githubusercontent.com/38451588/156770488-37c7c957-8714-483b-a736-505fa913abb9.png)
  
# Battery

![image](https://user-images.githubusercontent.com/38451588/156870880-9fcf778f-b965-4d5a-92fc-da179ddd72b6.png)


# Brochure

http://omolini.steptail.com/t3200sx/files/docs/Toshiba%20T1900%20T1950%20Series%20-%20Flyer.pdf

# Hard drive

- CP-2124 Conner 120MB 2.5-Inch 17mm IDE Notebook Hard Drive

![image](https://user-images.githubusercontent.com/38451588/156491386-d5c623de-c9ef-4468-9539-4d9eb9a41c10.png)


![image](https://user-images.githubusercontent.com/38451588/156871034-6c435c60-d7ba-4b57-91ee-421a28ddbb28.png)


# RAM/Memory

- 4MB standard (soldered on)

## RAM Upgrades

- RAM is added via a card (below is 16mb PA2014U):

![image](https://user-images.githubusercontent.com/38451588/156770009-b5a31e92-b70c-4d89-8a4e-81fec65d9db3.png)

![image](https://user-images.githubusercontent.com/38451588/156870898-7c398e1d-2b40-4710-807b-a32bcc39f4b2.png)


# Power Supply

- 18v, barrel connector. Center positive

![image](https://user-images.githubusercontent.com/38451588/156871013-5e82f4d0-70b8-4883-a396-40c6e5b23597.png)



# Disassembly

![image](https://user-images.githubusercontent.com/38451588/156870931-00ed93e5-aae6-4acd-ad27-808b983a3353.png)





- Remove 4 screws
- remove screw cap and 10mm screw above keyboard
- pop off cover
- unplug and set aside keyboard
- 4x screws for KB shield
- 6x 10mm screws top shield incl black earth lead
- 1x battery screw (RHS). Can now move battery out of the way and slide out HDD
- 2x 12mm screw next to the HDD connector
- 1x screw for hinge (RHS)
- Unplug screen display lead and sensor cable
- Unplug PS/2 flat cable
- 1x screw next to spkr
- Disconnect battery
- Disconnect PJ2
- Remove the small screw from the PCMCIA connector
- Remove screw near reset button (long)
- Remove screw near blue relay thingy (long)
- Unplug floppy


# Capacitors

6.3V 2200uF

25v 470uF

10v? 220uF

16v 120uF

16v 56uF

16v 120uF (duplicate?)

16v 56uF (duplicate?)

6.3v 1000uF




# Unverified/unsorted info

When the laptop is running from the AC adaptor, you press the switch to turn it on. After only a few seconds, it shuts itself off. The DC IN light may flash. If the laptop has a status LCD, it may display a P30 or P31 error.


If your laptop still runs off the battery without the adaptor plugged in, one solution is to just run off the battery, but that is rather inconvenient. To run the laptop off the adaptor requires you to replace a capacitor inside the laptop. I found opening up the laptop and then reassembling it to be difficult. All the parts are so physically integrated it's like a puzzle. First you have to remove the plastic piece surrounding the keyboard. To do so, first remove all the screws you can find. Then you need to unsnap the keyboard surround from the base. I used a very small, thin screwdriver (a knife might work well) to work around the seam and unsnap the keyboard surround from the lower half. I have only worked with the T1900C, so there may be differences from your model. Next you need to gain access to the power supply area, which in most if not all models is probably located near the DC IN jack. There will be a few large electrolytic capacitors in this area. You will probably have to remove the keyboard and several metal shields. In the T1900C it was necessary to remove the entire circuit board assembly and take it completely apart so I had the lower system board by itself.

Now you need to locate the bad capacitor. In a message on Computing.Net, a person with a T4600 reports replacing a 1000uF 6.3 volt capacitor. In the T1900C I found just such a capacitor, 1000uF 6.3VDC and after replacing it, the laptop works. It sounds like a similar power supply design was used in many models, so look for a capacitor with these specifications.

Once you have found the capacitor to replace, you need to remove the old one. For some reason it was extremely difficult for me to desolder the capacitor and I ended up just pulling the capacitor body off the leads and then removing the leads individually. After I removed the leads, the holes in the circuit board were filled with solder which I was able to remove using a desoldering braid.

Now you need to get a replacement capacitor. The physical dimensions of the replacement will be very important, so you'll need to measure how big of a capacitor you can fit in your model. Since the original capacitor failed, the circuit apparently stresses this component, so it is probably a good idea to get a capacitor made for durability, with high permissible ripple current / low ESR. I used a 1000uF 6.3VDC Elna capacitor which I bought from Mouser (item 555-6.3V1000). It was 2cm tall and 8mm in diameter, with 3mm lead spacing, but I managed to fit it in. However, it was a difficult fit, so you may want to look at other capacitors if you don't think this one would fit in your model. I also recommend getting some replacement fuses in case you blow some of them. Somehow I managed to blow a 5 amp fuse on the lower board which connects to the battery. Later in my experimenting I managed to blow both 2 amp fuses on the upper system board. I replaced the 5 amp SMD fuses with Mouser part 5762-451005. They have 2 amp fuses also, part 5762-451002. Some models may require different fuses. You can look for them on the circuit boards. The fuses should have the current rating printed on the body, like 5A or 2A.


# References

https://www.manualslib.com/manual/916932/Toshiba-T1900-Series.html

https://vobarian.com/toshibaProblem.html


http://www.computinghistory.org.uk/det/13145/Toshiba-T1900C/


