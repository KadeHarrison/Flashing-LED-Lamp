# Flashing-LED-Lamp
2nd project for the Shenzhen fallout event which uses more electrical components than the USB hub meaning it is slightly more complicated

**IMPORTANT NOTE**

At first it didn't look like the SVG files didn't export correctly but if you zoom in or have very good eyes you can see a very very thin red outline of the design. Sorry for the inconveniance.

__Flashing LED description__

This is my second project that goes towards the 60 hour total for the Shenzhen hackathon. My motivation for this project was to complete projects that I haven't completed before in my Systems class in the time given and fuse them together to make one whole new design/project. 

I began this project knowing that it will take quite a long time as I've had experience with making the two projects I am fusing which was making a flashing LED mechanism and an LED lamp. My thought process was mainly if I couldn't do these in the given time why not try again by fusing them together and completing them in the given time to fully show my improvementover the past couple years with project making.

Unlike the USB hub however I only used softwares that I was already confident with. This wasn't all negative though as I could work much faster and efficiently hopefully making the process easier for me.

**How it works**

ALthough I'm not too sure on the specifics of how it fully works I do know part of what happens. In Australia when you plug a USB adapter or charger to the wall the voltage automativcally drops from a massive and dangerously high voltage of 240V to a measly (In comparrison) 5 V. This means that I will not need a massively large resistor of who knows how many volts and just have 2 reistors of approximately 10k Ω connected to the lights and 2 resistors of approximately 330 Ω  connected to the transistors. That's lke pretty much what i know but I'll update this part later when I completely find out how it does.'

# Cad Designs

**Base designs**

<img width="1470" height="956" alt="Screenshot 2026-05-27 at 9 15 06 pm" src="https://github.com/user-attachments/assets/21ea86f3-ae6e-487c-a618-a2ed4245ad0f" />

This is an image of the bottom part of the base and the lid of the base right next to eachother

<img width="351" height="475" alt="Screenshot 2026-05-27 at 9 16 12 pm" src="https://github.com/user-attachments/assets/7c5dcf69-7233-4916-8f2e-d6f4bfca8e1a" />

This is an image of the inside of the bottom of the base by itself to enhance the view of it's hole

<img width="352" height="381" alt="Screenshot 2026-05-27 at 9 16 21 pm" src="https://github.com/user-attachments/assets/ffffd34c-9187-430d-a73e-0ccef539dac0" />

This is an image of the top of the lid of the base putting focus on the hole where the acrlyc piece will sit

<img width="1470" height="956" alt="Screenshot 2026-05-27 at 9 16 31 pm" src="https://github.com/user-attachments/assets/d7cae1d4-2906-4829-a1ff-b5bd32fd5556" />

This is an image of the holes on the short side of the lid where the switch and USB A wire will fit next to eachother

[Here is where you can access my Base parts](https://www.tinkercad.com/things/kC6gt5TjKM3-falloutdesign2-lamp/edit?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard%2Fdesigns%2F3d&sharecode=V-KT6zl6J-J6KWzli3JYsMJJHnUKUv7fYH-51g_30aU)

__Acrylic designs__

<img width="1470" height="956" alt="Screenshot 2026-05-27 at 9 37 58 pm" src="https://github.com/user-attachments/assets/e9acc147-9f5f-42cd-b061-5e4661206cf8" />

This is an image of all the different parts of the acrylic base all in the same image

<img width="558" height="452" alt="Screenshot 2026-05-27 at 9 38 26 pm" src="https://github.com/user-attachments/assets/666fd6bb-af19-487a-a19c-feda1d62a992" />

This is an image of the Goofball design which will be the main focus of the ACrylic design which is why it's so big

<img width="236" height="206" alt="Screenshot 2026-05-27 at 9 38 33 pm" src="https://github.com/user-attachments/assets/5b4fd2c9-9244-4d20-8149-3ca252933ba4" />

This is an image of the Text part of the acrylic design which is made to complement the Goofball design.

<img width="448" height="357" alt="Screenshot 2026-05-27 at 9 38 44 pm" src="https://github.com/user-attachments/assets/8974122e-a5c5-49a8-b93b-299fd28382ea" />

This is an image of the main acrylic part which will hold the other two design elements on it.

[Here is where you can access my acrylic designs](https://www.tinkercad.com/things/1KeQmNdhhAh-fallout-acrylicdesign/edit?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard%2Fdesigns%2F3d&sharecode=WiNNvY0Naw_Fd4pKn8BLqupI097vY8Rgafzn0IhOWRQ)

# Specs

2 LEDs:

1x red LED and 1 x blue LED

2x 100µF 25V capacitors

4 resistors:

2x 10 kΩ resistors and 2 x 330Ω

2x PNP tansistors

1x Small breadboard

# BOM

__Note: all prices are in AUD so translate it into your personal currency for actual price that relates to you__

**Other note: If your purchasing by all the parts from that website at the same time for cheapest shipping**

| Item | Cost | Shipping cost (Only displayed if shop isn't within reasonable distance of me) | Total price (Shipping + normal cost) |Purpose | Website | Needed / not needed for funding for the fallout event | Link |
|------|------|---------------|--------------------------------------|---------|---------|-----------------------------------------------|------|
| blue LED 5mm 350mcd | $0.95 | not needed for me | $0.95 | To act as  one of the lights that light up the acrylic part | Jaycar | not needed | https://www.jaycar.com.au/blue-5mm-led-350mcd-round-diffused/p/ZD0185 |
| White LED 5mm  4000mcd |  $1.15 | not needed for me | $1.15 | To act as the other light source that will flash with the blue one to light up the acrylic | Jaycar | not needed | https://www.jaycar.com.au/white-5mm-led-4000mcd-round-clear/p/ZD0190 |
| 100µF capacitor x 2 | 0.28 x 2 = $0.56 | $7.00 | $7.56 | | Core Electronics | no needed | https://core-electronics.com.au/radial-capacitor-100uf.html |
| 10 kΩ resistors x 2 | $1.65 (no multiplying needed as its a 20 pack) | $7.00 | $8.65 | to be able to connect the LEDs to the circuit without frying them | Core Electronics | no needed | https://core-electronics.com.au/resistor-10k-ohm-1-6th-watt-pth-20-pack.html |
| 330Ω resistor x 2 | $2.25 (no multiplying needed as its a 20 pack) | $7.00 | $9.25 | Tp be able to connect the transistors to the circuit without frying them | Core Electronics | not needed | https://core-electronics.com.au/resistor-330-ohm-1-4-watt-pth-20-pack-thick-leads.html |
| PNP transistor x 2 | $3.90 (No multiplication needed as it includs 5x NPN and 5x PNP transistors meaning you can use the extras for other projects | $7.00 | $10.90 | | Core Electronics | Not needed | https://core-electronics.com.au/bipolar-transistor-kit-5-x-pn2222-npn-and-5-x-pn2907-pnp.html |
| Small Breadboard | $9.55 | $7 | $16.55 | To provide a place to connce all the different electrical components | Core Electronics | not needed | https://core-electronics.com.au/professional-solderless-breadboard-400-tie-points-metal-backing-plate.html|
| 4.5mm thick creal acrylic 300mm x 200mm | $5.38 | $16.00 | $21.38 | To provide a base to cut with a laser cutter and light up with the LEDs | Koenig Machinery | not needed | https://koenigmachinery.com.au/products/clear-acrylic?variant=53416314405032 |
| 3D printing PLA 1Kg | $23.98 | $7.95 | $31.85 | To have PLA for 3D printing the base | Inkstation | not needed | https://www.inkstation.com.au/2102/1-pla-3d-filament-175mm-red-1kg-p-12246.html |
| Bambu lab mini printer | $319 | not needed for me | $319 | To print out the base of the lamp | Officeworks | not needed | https://www.officeworks.com.au/shop/officeworks/p/bambu-lab-a1-mini-3d-printer-bama1m |
| CO2 laser cutter | $2,850 - $10,000 depending on eddition bought | $0 | $2,850 - $10,000 depending on ediion | To cut the acrylic | Style CNC | not needed | https://www.stylecnc.com/co2-laser-cutting-machine/best-co2-laser-cutter.html |
