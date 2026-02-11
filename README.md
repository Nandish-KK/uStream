### Update! This project has been abandoned for a while. Looking back at the design, there are fundamental design erros in terms of isolation, analog temperature sensing and more. I still do use it regularly but not recommend to design the exact thing. Feel free to explore the schematic for your own reference.

A few weeks ago, I wanted to buy a hot air station for some smd rework. While I was searching for one, I came across lot of Chinese hot air stations which seem to be dirt cheap and also seem quite reliable. However the problem is that, these seem to be outdated design and somewhat lack in safety!
On the other hand the offerings from top players like JBC and Wellers seems to be out of reach for any hobbyist.

I guess these are enough excuses for making my own hot air station. Since I cannot make the core components (The Heater and air pump units) I will be working on the controller unit. The heater and pumps can be purchased easily through any online repair parts sellers or even better if you could directly buy from Chinese sites like aliexpress. 

I will try to add everything I have cooked so far in the coming days.

![micro_stream](./Pictures/uStream_cover.png)

Edit: As of now everything on hardware is tested and corrected in schematics/PCB. The idea of implementing the thermo-couple amplifier using an precision op-amp has to be scratched since, I can't figure out the problem with my current setup (glad I implemented the MAX6675 as a backup!).
Although I have run basic software tests, there is still more code to test thoroughly.

![p1](./Pictures/Render.png)

![p2](./Pictures/Inside.png)

![Schematic](./Pictures/Schematic_uStream.png)
*Version 2 Schematics*

