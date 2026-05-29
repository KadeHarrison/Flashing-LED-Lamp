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
| CO2 laser cutter | $2,850  | $0 | $2,850  | To cut the acrylic | Style CNC | not needed | https://www.stylecnc.com/co2-laser-cutting-machine/best-co2-laser-cutter.html |
| Solder | $7.98 | Free (In my location at least | $7.98 | To be able to stick the wires together to prevent lose wires that may cause any problems and so it looks neat in general | Amazon | not needed | https://www.amazon.com.au/Solder-Welding-Electronic-Components-Soldering/dp/B0F26B8TSQ/ref=asc_df_B0F26B8TSQ?mcid=b2edce23f18a3cec8209330a88a9fec3&tag=googleshopdsk-22&linkCode=df0&hvadid=712291433914&hvpos=&hvnetw=g&hvrand=15429142978442473764&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9071204&hvtargid=pla-2424025594741&psc=1&hvocijid=15429142978442473764-B0F26B8TSQ-&hvexpln=0&gad_source=4 |
| Soldering station | $59.95 | $9.95 | $69.99 | To heat up the solder so that it actually melts | Jaycar | not needed | https://www.jaycar.com.au/duratech-48w-temperature-controlled-soldering-station/p/TS1620?srsltid=AfmBOopg5HbUDk4L01GgtBI5sMikfJQgY-JY1OWJXv0Hm5q5vl4yxGqWA8s |
| Solder tip cleaner | $10.88 | $5.40 | $16.28 | To clean the soldering iron if the tip gets too messy and prevents the solder from being melted | Amazon | not needed | https://www.amazon.com.au/Soldering-Reusable-Refresher-Equipment-Maintenance/dp/B0D424RWR8 |
| Fume extractor | $42.99 | Free delivery | $42.99 | To prevent the inhalation of any toxic fumes while soldering | Amazon | not needed | https://www.amazon.com.au/Fume-Extractor-Fan-Prevention-Ventilation/dp/B0DDT7C37V/ref=asc_df_B0DDT7C37V?mcid=e85889876c8f35ca9038900549800bd6&tag=googleshopdsk-22&linkCode=df0&hvadid=712291433908&hvpos=&hvnetw=g&hvrand=7959543567787614393&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9071204&hvtargid=pla-2393387151819&psc=1&hvocijid=7959543567787614393-B0DDT7C37V-&hvexpln=0&gad_source=1 |
| Solder mat | $3.13 | Free delivery | $3.13 | To make sure you don't make a mess while soldering by providing a small work plane for things to drop on safely | Temu | not needed | https://www.temu.com/au/1pc-silicone-repair-mat-for-electronics-magnetic-soldering-pad-insulated-welding-mat-for-bga-welding-iron-workbench-protector-for-phone-laptop-repair-no-battery-required-g-601099524480864.html?top_gallery_url=https%3A%2F%2Fimg.kwcdn.com%2Fproduct%2FFancyalgo%2FVirtualModelMatting%2F88fc24dab1fe83f61c3d405ebf13e198.jpg&spec_gallery_id=0&sku_id=17592251151053&share_token=wuUPTXTbIWU4YtMPpGT6BQ_dekTHwjnl85YlzVHVHLKyg9jCAf1LaRGPHnSbr5_YmdN2ZlcOBZzYIhEFhc7j8YyodFTDmyTepnDC6BdFXd1y8tg7fVV0SFytRqZan08Z&_x_vst_scene=adg&_x_ads_sub_channel=shopping&_x_ns_prz_type=-1&_x_ns_sku_id=17592251151053&_x_ns_gid=601099524480864&_x_ads_channel=google&_x_gmc_account=710728018&_x_login_type=Google&_x_ns_gg_lnk_type=adr&_x_ads_account=5483888441&_x_ads_set=23023233052&_x_ads_id=186276689998&_x_ads_creative_id=774124430609&_x_ns_source=g&_x_ns_gclid=Cj0KCQjwz9_QBhD_ARIsADnSCfCAf3V64VysS-ye-WdYd6PNZgRzjRu7o3SKsho4U5jklQZMrAUw3rcaAlQvEALw_wcB&_x_ns_placement=&_x_ns_match_type=&_x_ns_ad_position=&_x_ns_product_id=710728018-17592251151053&_x_ns_target=&_x_ns_devicemodel=&_x_ns_wbraid=CkAKCAjwz9_QBhA5EjAADkvjjKyeT71Id6Y2TRPacNZKA62ld8muB1AdwNDyfVEaHNAAOeguzqeRbaMeG_MaArtO&_x_ns_gbraid=0AAAAAo4mICE8gkPyIQBXedxB0jC9xbtsL&_x_ns_targetid=pla-2480940157101&refer_page_name=kuiper&refer_page_id=13554_1780035015490_mtwkj5jk2t&refer_page_sn=13554&_x_sessn_id=7i7ei4g36n |
|Wire strippers | $6.59 | Free shipping | $6.59 | To strip part of the USB A connecter to connect it to the ccircuit | Temu | not needed | https://www.temu.com/au/professional-wire-stripping-and-crimping-tool-stain-resistant-and-rust-resistant-polished--ginger-black-handle-with-scale--0-24mm2-cable-and-wire-cutting-tool-wire--g-601099580055097.html?top_gallery_url=https%3A%2F%2Fimg.kwcdn.com%2Fproduct%2Ffancy%2Faaeaf503-5f1f-46ef-8d75-d6f2ee01dbb1.jpg&spec_gallery_id=0&sku_id=17592463966181&share_token=wuUPTXTbIWU4YtMPpGT6B6R2q0ilAoHN2beovYmL8wNiMZNUjOIYRGnaBsP51wAL_tHsQPVQN61-shk-Zftw2-CUJZOotfkFbgEMF0oKttlM0ehcbdbFk0JCTzPVLJV2mGjgM_ekjLe9fE81S5_A4ORS7S7ZCX2_N-YYgbn-GNH&_x_vst_scene=adg&_x_ads_sub_channel=shopping&_x_ns_prz_type=-1&_x_ns_sku_id=17598339067418&_x_ns_gid=601101118719935&_x_ads_channel=google&_x_gmc_account=710728018&_x_login_type=Google&_x_ns_gg_lnk_type=adr&_x_ads_account=5483888441&_x_ads_set=22918635529&_x_ads_id=182500463165&_x_ads_creative_id=770310249500&_x_ns_source=g&_x_ns_gclid=Cj0KCQjwz9_QBhD_ARIsADnSCfBAc1y1mDSaYqPyeaMwxD1PpNm4g1zks3AqFgKjyK8Ln8TW4r4_zOoaAlriEALw_wcB&_x_ns_placement=&_x_ns_match_type=&_x_ns_ad_position=&_x_ns_product_id=710728018-17598339067418&_x_ns_target=&_x_ns_devicemodel=&_x_ns_wbraid=CkAKCAjwz9_QBhA5EjAADkvjjDaD0PsoYYEJGUDzCYuEPInOX-GwzFMk-VuWHgu-o6uATHLeQxJgU69NsIUaAiGF&_x_ns_gbraid=0AAAAAo4mICFxgdkw-ON7H5ZwnWz70U019&_x_ns_targetid=pla-2521130445357&refer_page_name=kuiper&refer_page_id=13554_1780035159781_fjg462dumr&refer_page_sn=13554&_x_sessn_id=tgbughnrmd |
| USB A connector | $1.21 | $8.25 | $9.46 | to connect the circuit to a power source in the form of wall outlets | Ebay | not needed | https://www.ebay.com.au/itm/177675521459?chn=ps&_ul=AU&var=477287401745&norover=1&mkevt=1&mkrid=705-139619-5960-0&mkcid=2&mkscid=101&itemid=477287401745_177675521459&targetid=2365752142950&device=c&mktype=pla&googleloc=9071204&poi=&campaignid=21776459266&mkgroupid=171915223801&rlsatarget=pla-2365752142950&abcId=10047394&merchantid=548726319&gad_source=1&gad_campaignid=21776459266&gbraid=0AAAAAD97CxR6euxju-p0_CeaqGWccHJCr&gclid=Cj0KCQjwz9_QBhD_ARIsADnSCfDyJGnIaaxtNMRF_VAJ0PiDKeXV2PYTjRrjIQGTuL0qejvjJ9387j8aAhZFEALw_wcB |
| male - male wires | $3.74 | Free delivery | $3.44 |to connect all the components in a circuit | Temu | not needed | https://www.temu.com/au/40-120pcs-high-quality-3-94-ft--jumper-wire-kit--in-female-to-female-male-to-female-and-male-to-male---robot-projects-builds-and-learning-g-601103179287010.html?top_gallery_url=https%3A%2F%2Fimg.kwcdn.com%2Fproduct%2Ffancy%2F68007042-3f40-4079-bd29-45a130e1bcea.jpg&spec_gallery_id=0&sku_id=17608427540400&share_token=wuUPTXTbIWU4YtMPpGT6Bnrav-nDwqnEUXwmaopgtZ5xulP661IySLooJ9RCRcvjCaBFrIGaFwKRv2P_1KfSHHtqEHvBpx0Eb6nnIHjqzoI0m1WoQmKrU67nClnNh_VmVJ1km6MisCSjgbLKH4Af3K8QIgmIVTCbz0FZ60hmP-E&_x_vst_scene=adg&_x_ads_sub_channel=shopping&_x_ns_prz_type=-1&_x_ns_sku_id=17608427540400&_x_ns_gid=601103179287010&_x_ads_channel=google&_x_gmc_account=710728018&_x_login_type=Google&_x_ns_gg_lnk_type=adr&_x_ads_account=5483888441&_x_ads_set=22869377734&_x_ads_id=186350966351&_x_ads_creative_id=767800951803&_x_ns_source=g&_x_ns_gclid=Cj0KCQjwz9_QBhD_ARIsADnSCfBKUTARE7QV3v_8vGGENVYLc63uNCXKvJl4s7Aw2IWQKcMiXJ0eNIYaAkpfEALw_wcB&_x_ns_placement=&_x_ns_match_type=&_x_ns_ad_position=&_x_ns_product_id=710728018-17608427540400&_x_ns_target=&_x_ns_devicemodel=&_x_ns_wbraid=CkAKCAjwz9_QBhA5EjAADkvjjDy9b6TwiAWKB11O6P0P1djTd_pdqCVkXiAxEDt24161FORQqYP7UmrNhnMaArWj&_x_ns_gbraid=0AAAAAo4mICGa3SBOVvMLTxApb4jo-4G_g&_x_ns_targetid=pla-2455998651775&refer_page_name=kuiper&refer_page_id=13554_1780035951432_mn4xbzgcws&refer_page_sn=13554&_x_sessn_id=zkaiul1ldv |
| Switch | $4.95 | $9.95 | $14.9 | to be able to manually turn the circuit on and off | Jaycar | not needed | https://www.jaycar.com.au/dpdt-large-rocker-switch/p/SK0981?srsltid=AfmBOopu6eM_QkYCPlHLt_bO7zgGlsJs2M9kQFyUVgoc3fvsGoGHWTa0fbw |
| Totals | Price total: $3359.79 | shipping total:$92.5 | All together total: $3452.79 |
