this repo is for the design of a desk display

the display will have at least 3 modes.

1. off
2. low
3. high

an STM32 will be utilised for logic of the LEDs

the display will need to be powered off 5v usb power. no batteries required.

inspiration for this design is taken from this product [link](https://www.amazon.com.au/iDotMatrix-Programmable-Creative-Animations-Accessories/dp/B0CGJ57Y9M/ref=dp_prsubs_d_sccl_1/355-4629694-3403445?pd_rd_w=Hvg2Z&content-id=amzn1.sym.ee7e9416-0067-4952-bd69-db7b20590edd&pf_rd_p=ee7e9416-0067-4952-bd69-db7b20590edd&pf_rd_r=XX34ZCR8BBGWM05KNYQZ&pd_rd_wg=RwuEd&pd_rd_r=22dadd65-7443-4378-a1fc-f7a6b80b33fc&pd_rd_i=B0CGJ57Y9M&th=1)

it's 100 bucks on amazon so i will try to make it on about that budget.

the display will show an uploaded black and white picture which can be changed through reprogramming the STM32

the LED display will reverse the colour so black becomes white and white becomes black. the display will have a black background and white LEDs.

BOM below:

| ITEM | LINK | Description | QTY |   PACKAGE QTY |PRICE EACH | PRICE PACKAGE |
|-----|----------|-------------|-----|----------|----------|-------------|
| LED display | [link](https://www.digikey.com.au/en/products/detail/luckylight/KWM-20881AVA/14009060)    | Picture Display | 100|  100 | 1.2 | 120 |
| STM32F103x8 | [link](https://www.temu.com/au/-f103c8-arm--ch32f103c8-system-development-board-module-for--g-605811375965650.html?_oak_mp_inf=ENKL9p6334kBGiA2YjAzZGYxZjcxZDU0NDUwYTc1NzNmZWJiM2M1MzRjMyDT%2FZnA7jM%3D&top_gallery_url=https%3A%2F%2Fimg.kwcdn.com%2Fproduct%2Ffancy%2Ffd220ded-5b59-4012-b1e9-bd9bee3e90d8.jpg&spec_gallery_id=32459483419&refer_page_sn=10009&freesia_scene=2&_oak_freesia_scene=2&_oak_rec_ext_1=MTA1Mw&_oak_gallery_order=1499744445%2C373524183%2C114294326%2C2080611673%2C1413852090&search_key=STM32&refer_page_el_sn=200049&_x_sessn_id=s0u1qxklql&refer_page_name=search_result&refer_page_id=10009_1782009201692_bazxidpeid)  | Logic | 1 |   1 |10.53| 10.53 |
| 3 way switch | [link](https://www.digikey.com.au/en/products/detail/gct/SWS040-015V23SSA/29426307)     | user input | 1 |   1 |.82 | .82|
| TOTAL PRICE |  |  |  |  |  | 131.35 |


the LEDs are actually quite expensive. it might be cheaper to design my own LED display from scratch. I'll cover that in a different repo.

arguably using these led arrays will give a better resolution when compared with the amazon product above. so maybe the extra 50 bucks is worth it.

however this design does not include app level programming or different colours so most consumers might go for the amazon product but hey this is more a learning experience then anything so lets just accept that we need to spend some money to make something good. we can improve the design later down the track.



