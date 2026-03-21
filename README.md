# Micro Mechanical Collector
### Hack Club Hardware Project


<img width="584" height="450" alt="Знімок екрана 2026-03-05 о 22 10 29" src="https://github.com/user-attachments/assets/09d74bf5-e80d-4c25-8742-1e78feb6957b" />

A compact **7 cm micro-mechanical prototype** designed to explore small-scale mechanical lifting, modular robotics, and structural wire frameworks.

The project investigates how **thin mechanical structures can slide under objects and apply lifting force through leverage and pivot motion**.

---

# Overview

The **Micro Mechanical Collector** is a small mechanical system designed to:

- Slide under small objects
- Apply lifting force through mechanical leverage
- Connect with other units to increase lifting capability
- Demonstrate principles of **micro robotics and mechanical engineering**

The device uses a **1.75 mm wire structural frame**, pivot joints, and a compact geometry allowing it to operate in tight spaces.
---

## CAD Model

<img width="284" height="712" alt="image" src="https://github.com/user-attachments/assets/3331fd57-7bb6-464c-86d1-0c80664998a1" />


## Exploded View



---

## Mechanical Diagram
<img width="718" height="369" alt="image" src="https://github.com/user-attachments/assets/d474ed8b-e49f-48b2-ba90-57709980179e" />



*Illustration showing the lifting mechanism.*

---

# Specifications

| Property | Value |
|--------|--------|
Length | 77 mm |
Wire Diameter | 1.75 mm |
Frame Weight | ~25–40 g |
Load Capacity | 80–120 g |
Joint Diameter | 2 mm |
Structure Type | Wire mechanical frame |

---

# System Architecture

The system consists of five main components:

1. **Central frame body**
2. **Front sliding arms**
3. **Rear stabilizing structure**
4. **Pivot joint**
5. **Control linkage**

Each part is designed to maintain **compact geometry while maximizing lifting leverage**.

---

# Mechanical Principle

The mechanism operates using **pivot rotation and leverage**.

Process:

1. The angled front arms slide under an object.
2. Force applied to the rear structure rotates the arms.
3. The pivot converts horizontal force into lifting force.

This follows the **lever equation**:
Torque=Force*Distance
Where the pivot acts as the **fulcrum**.

---

# Multi-Unit Interaction

Multiple collectors can combine to increase lifting capability.

Example structure:
Unit A--- Unit B--- Unit C

Connecting units distributes the load across multiple frames.

Estimated combined lifting capacity:

| Units | Load |
|------|------|
1 | 100 g |
3 | 250 g |
10 | 300 g+ |

---

### 🛠 Component Specifications (Standard Unit)

#### 1. Control & Logic

| Component | Specification | Purpose |Costs| Link and place|
| :--- | :--- | :---| :---|:---|
| **Microcontroller** | Seeed Studio XIAO ESP32-C3 | Tiny footprint with built-in Wi-Fi/Bluetooth and Li-Po charging. Perfect for swarm mesh. |£6.30|[aliexpess](https://www.aliexpress.com/item/1005008304166336.html?spm=a2g0o.productlist.main.7.374c539aUrI4BN&algo_pvid=d65f321b-c400-4973-a734-3a40435b9bdf&algo_exp_id=d65f321b-c400-4973-a734-3a40435b9bdf-6&pdp_ext_f=%7B%22order%22%3A%22518%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21GBP%217.00%216.30%21%21%2162.60%2156.34%21%40211b80d117727542178938242eec89%2112000044555521521%21sea%21UK%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A5dc664df%3Bm03_new_user%3A-29895&curPageLogUid=VqoXI7G1IoCv&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008304166336%7C_p_origin_prod%3A)|
| **Motor Driver** | DRV8833 (Mini) | Dual-channel H-bridge. Controls the lifting actuator and the drive motors. |£3.55|[aliexpress](https://www.aliexpress.com/item/1005010465908236.html?spm=a2g0o.productlist.main.2.5fc8QAJwQAJwMd&algo_pvid=9acf3f4c-cede-44b8-aeae-caaedfdadb10&algo_exp_id=9acf3f4c-cede-44b8-aeae-caaedfdadb10-1&pdp_ext_f=%7B%22order%22%3A%227%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21GBP%218.07%213.55%21%21%2172.16%2131.75%21%40210388c917727551283058947ee23e%2112000052505769487%21sea%21UK%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A5dc664df%3Bm03_new_user%3A-29895&curPageLogUid=PYnAs2ctEQt0&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010465908236%7C_p_origin_prod%3A)|
|Capacitors |||£4.49|[amazon](https://www.amazon.co.uk/100uF-Radial-Aluminium-Electrolytic-Capacitor/dp/B07CZJC2GJ#:~:text=100uF%2010V%20radial%20aluminium%20electrolytic%20capacitors.,reliability%20and%20high%20ripple%20current.)|
|MOSFET SI2302|||￡1.27|[Aliexpress](https://www.aliexpress.com/item/1005006983006733.html?UTABTest=aliabtest125094_24785&src=google&src=google&albch=shopping&acnt=494-037-6276&slnk=&plac=&mtctp=&albbt=Google_7_shopping&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005006983006733&ds_e_product_merchant_id=5354033553&ds_e_product_country=GB&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=17859500389&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=17190468917&gbraid=0AAAAADznYb8uI_IngBqfvvTT8bqOIiH71&gclid=Cj0KCQiAk6rNBhCxARIsAN5mQLtvmAGvH31rG8joUcPBKZUsjq_D4-_51fwsJESKpRrV0P-_pdfKb40aAiTHEALw_wcB&aff_fcid=c3bb0a1d9de649edb9a69db0bddcd448-1772796621083-01433-irey5Th&aff_fsk=irey5Th&aff_platform=promotion&sk=irey5Th&aff_trace_key=c3bb0a1d9de649edb9a69db0bddcd448-1772796621083-01433-irey5Th&terminal_id=104e0389bed649eda5304ec4638a1262&OLP=1116833308_f_group2&o_s_id=1116833308&afSmartRedirect=n)|
|Resistors|||£5.49 |[amaozn](https://www.amazon.co.uk/Innfeeltech-Tolerance-Resistor-Resistance-Experiments/dp/B0CL73CZPQ/ref=sr_1_6?dib=eyJ2IjoiMSJ9.ag45F5GOEYgbj0nJDUDr_BpAwDChfL65S5JWa42vMhHXSLcesGCL7rdPrtGo3KK0NURx7ULoRl1vWXXgYMGITxFc6DLlBlT2Ti0YfaQm0DvTMUShnwR4KyFwTIMVZNHLP6_bJxagBRX2-zd2aD-I64fCcn9RGCZW-Sli0DpLZ8G9l0tHDjbv3xEQ4qwAlfA1lN3fyfSotY77hveSERT0Ls0zCY5RpklPMy64Gh4hzok9y-MJjhGLyIEiFnALA6asRvsWaKe44JVOyjtK160hV2Htr6n8dH8um8W5UfeS1-U.ut3RRab1b0RM2qyixTeH_EkpbnWsRjv8QgD9L5RKtSg&dib_tag=se&keywords=10k%2Bresistor&qid=1772796797&sr=8-6&th=1)|


#### 2. Drive & Mechanics

| Component | Specification | Purpose |Cost|Link and Place|
| :--- | :--- | :--- |:---|:---|
| **Lifting Motor** | 6mm Coreless Motor + Gearbox (1:136) | Provides the high torque required for the leverage pivot system. |£7.19|[amazon](https://www.amazon.co.uk/sourcingmap-1-5V-4-5V-40000RPM-Speed-Coreless/dp/B01480X6IK)
|Vibration Motors |10mm Flat Coin Motors 3.7V | | ￡0.50|[Aliexpress](https://www.aliexpress.com/item/1005006821274949.html?UTABTest=aliabtest125094_24785&src=google&src=google&albch=shopping&acnt=494-037-6276&slnk=&plac=&mtctp=&albbt=Google_7_shopping&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005006821274949&ds_e_product_merchant_id=5337730398&ds_e_product_country=GB&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=17859500389&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=17190468917&gbraid=0AAAAADznYb8uI_IngBqfvvTT8bqOIiH71&gclid=Cj0KCQiA8KTNBhD_ARIsAOvp6DLoYMNrAQmteEOsgQxlXuzJDoOqxjrhlZ8_qD0jz3fbyDbNx6rzPZsaAnLdEALw_wcB&aff_fcid=3b4e5678b05346cbb792b93ed54c64eb-1772794924822-07320-irey5Th&aff_fsk=irey5Th&aff_platform=promotion&sk=irey5Th&aff_trace_key=3b4e5678b05346cbb792b93ed54c64eb-1772794924822-07320-irey5Th&terminal_id=104e0389bed649eda5304ec4638a1262&OLP=1116833308_f_group2&o_s_id=1116833308&afSmartRedirect=n)
| **Structural Wire** | 1.75mm Brass Rod | Superior to plastic; allows for a rigid, solderable, and heavy-duty frame.|£3.89|[amazon](https://www.amazon.co.uk/sourcing-map-Crafts-Helicopter-Airplane/dp/B0FBS13Q67/ref=asc_df_B0FBS13Q67?mcid=17bfe8f9ded53024b9efc60dadbd3f65&tag=googshopuk-21&linkCode=df0&hvadid=750632708281&hvpos=&hvnetw=g&hvrand=15926334436493289098&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9045084&hvtargid=pla-2442856562608&hvocijid=15926334436493289098-B0FBS13Q67-&hvexpln=0&gad_source=1&th=1)

#### 3. Energy System (Power Sharing)

| Component | Specification | Purpose |Costs|Link and Place|
| :--- | :--- | :--- |:---|:---|
| **Battery** | 3.7V 150mAh Li-Po (20C) | Lightweight (~5g) power source for 15-20 minutes of active operation. |£7.49 |[amazon](https://www.amazon.co.uk/Rechargeable-Replacement-Connector-Aircraft-Accessory/dp/B0CRPF71VW?th=1)
| **Contact Pads** | Copper Foil / Gold-plated pads | Conductive surface for energy transfer between docking units. |£3.99|[amazon](https://www.amazon.co.uk/kanta-Adhesive-Repellent-Deterrent-Barrier/dp/B0DHXBQ84S/ref=asc_df_B0DHXBQ84S?mcid=7aafc9c59e6a3fb3b57495e45b31d208&tag=googshopuk-21&linkCode=df0&hvadid=715474129867&hvpos=&hvnetw=g&hvrand=14379906696448413497&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9045084&hvtargid=pla-2371988249679&hvocijid=14379906696448413497-B0DHXBQ84S-&hvexpln=0&gad_source=1&th=1)
| **Magnets** | Neodymium N52 (3x2mm) | High-strength magnets to ensure secure physical and electrical docking. |50  £5.79|[amazon](https://www.amazon.co.uk/Spider-Magnetics-Ltd-Neodymium-miniatures/dp/B00YYJDYRY?th=1)|
|Pogo Pins|||￡1.43|[Aliexppress](https://www.aliexpress.com/item/1005006003522295.html?spm=a2g0o.productlist.main.9.59fbzqYrzqYrZE&algo_pvid=78af986c-a9e5-4e5d-9fc1-df77e796e140&algo_exp_id=78af986c-a9e5-4e5d-9fc1-df77e796e140-8&pdp_ext_f=%7B%22order%22%3A%22412%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21GBP%211.43%210.76%21%21%211.85%210.98%21%40211b807017727961851112906e7dad%2112000035311316238%21sea%21UK%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A5dc664df%3Bm03_new_user%3A-29895%3BpisId%3A5000000197842823&curPageLogUid=Z6Qd6fPoXisu&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006003522295%7C_p_origin_prod%3A)|
|MT3608 Mini Boost Converter |||£3.79 each|[Ebay](https://www.ebay.co.uk/itm/314844711292)|

#### 4. Navigation Sensors
| Component | Specification | Purpose | Costs |link and place|
|:---|:---|:---|:---|:---|
| **Distance Sensor** | VL53L0X (ToF) | Laser ranging for millimeter precision when sliding under objects. |£5.90|[ebay](https://www.ebay.co.uk/itm/196738317272)|
| **IMU** | MPU6050 (6-Axis) | Monitors pitch and tilt to prevent the robot from flipping during heavy lifts. |£7.77|[ebay](https://www.ebay.co.uk/itm/315404237156)

#### 5. Wiring 
| Component | Costs |link and place|
|:---|:---|:---|
|Schottky Diodes|£1.80 |[Amazon](https://www.amazon.co.uk/DIODES-1N4001-Rectifier-Diode-DO-41/dp/B08TQQGWH3/ref=asc_df_B08TQQGWH3?mcid=54536633b3b23214a45411aca279f4b6&tag=googshopuk-21&linkCode=df0&hvadid=761130755654&hvpos=&hvnetw=g&hvrand=12783311810980256032&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9045084&hvtargid=pla-2356814575831&psc=1&hvocijid=12783311810980256032-B08TQQGWH3-&hvexpln=0&gad_source=1)|
|Power (26 AWG)|￡2.03|[aliexpress](https://www.aliexpress.com/item/1005009192506490.html?UTABTest=aliabtest125094_24785&src=google&src=google&albch=shopping&acnt=494-037-6276&slnk=&plac=&mtctp=&albbt=Google_7_shopping&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005009192506490&ds_e_product_merchant_id=5589460369&ds_e_product_country=GB&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=17859500389&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=17190468917&gbraid=0AAAAADznYb8uI_IngBqfvvTT8bqOIiH71&gclid=Cj0KCQiA8KTNBhD_ARIsAOvp6DIf7Guv7Zw-pvBo1oZ0n6fnbNufuZrGnkbJNw0GUeWm4cVvlhZj5UwaAn5mEALw_wcB&aff_fcid=2c8daba505bf4926a73734e67b55533b-1772756764637-00392-irey5Th&aff_fsk=irey5Th&aff_platform=promotion&sk=irey5Th&aff_trace_key=2c8daba505bf4926a73734e67b55533b-1772756764637-00392-irey5Th&terminal_id=104e0389bed649eda5304ec4638a1262&OLP=1116833308_f_group2&o_s_id=1116833308&afSmartRedirect=n)|
|signall (30 AWG)|￡2.04|[Aliexpress](https://www.aliexpress.com/item/1005009192506490.html?src=google&pdp_npi=4%40dis!GBP!1.92!0.94!!!!!%40!12000048287693686!ppc!!!&snpsid=1&src=google&albch=shopping&acnt=494-037-6276&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&&albagn=888888&&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en1005009192506490&ds_e_product_merchant_id=5551326180&ds_e_product_country=GB&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=17859500389&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=17190468917&gbraid=0AAAAADznYb8uI_IngBqfvvTT8bqOIiH71&gclid=Cj0KCQiA8KTNBhD_ARIsAOvp6DIiDGbwIYMJeBfpARhjlNUDZMPshA1z70yOEkxu3Q5Hz9CEIYlMttkaAujgEALw_wcB)|
|32 AWG|￡0.79|[Aliexpress](https://www.aliexpress.com/item/1005004167126040.html?spm=a2g0o.productlist.main.22.5e5d132byPrkNI&algo_pvid=2e6809a4-04b5-451b-aad1-7471a426f873&algo_exp_id=2e6809a4-04b5-451b-aad1-7471a426f873-21&pdp_ext_f=%7B%22order%22%3A%223187%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21GBP%210.98%210.76%21%21%211.27%210.99%21%40211b80f717727572707874706ebc09%2112000028255058905%21sea%21UK%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A5dc664df%3Bm03_new_user%3A-29895%3BpisId%3A5000000197842823&curPageLogUid=A4sFK4SApuFv&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005004167126040%7C_p_origin_prod%3A)|
|Silver Conductive Glue|£5.83|[Amazon](https://www.amazon.co.uk/Silver-Conductive-Repair-Electronic-Circuit/dp/B0D3F4T8QW/ref=asc_df_B0D3F4T8QW?mcid=fb607c22ffcf30f8b439747b82d738ef&tag=googshopuk-21&linkCode=df0&hvadid=784821928493&hvpos=&hvnetw=g&hvrand=17510825728016960800&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9045084&hvtargid=pla-2461337263852&psc=1&hvocijid=17510825728016960800-B0D3F4T8QW-&hvexpln=0&gad_source=1)|


Final total: £81.33
---

# CAD Design

The model was created using fusion 360

# Diagram Structure

<img width="619" height="407" alt="image" src="https://github.com/user-attachments/assets/e0c9f46e-712d-4e62-8068-8f9522ac0b4d" />


## Top View

<img width="360" height="710" alt="image" src="https://github.com/user-attachments/assets/42445f62-3c43-44d0-ba78-0319b9eb34bd" />

---

## Side View

<img width="707" height="269" alt="image" src="https://github.com/user-attachments/assets/5b905d79-52ec-455f-8dac-44008025123a" />

---

# Joint Design

The pivot joint enables controlled rotation.

<img width="459" height="203" alt="image" src="https://github.com/user-attachments/assets/84222ae0-b6a0-427c-8d07-7a2ca8501132" />


# Future Improvements

Possible upgrades:

- micro-servo powered movement
- magnetic coupling between units
- stronger alloy frame
- automated control system
- swarm mechanical coordination

---
## Electronics Overview

Battery → ESP32-C3 → MOSFET → Motor

- ESP32 controls the motor
- MOSFET switches power to the motor
- Battery powers the entire system
 ## Reproducibility

All CAD files, components, and instructions are included so the project can be rebuilt without additional assumptions.

# Author

**Arsen Odemchuk**

Student researcher exploring:

- mechanical systems
- robotics
- physics prototypes
