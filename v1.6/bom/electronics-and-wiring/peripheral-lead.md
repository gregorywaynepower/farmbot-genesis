---
title: "Peripheral Lead"
slug: "peripheral-lead"
description: "These extra leads make it easy to connect new, additional peripherals to your Farmduino."
cad: https://cad.onshape.com/documents/728fa8fdb342a040fe0ca4b5/w/0435033a7c78b02e71d0f721/e/bd682ae8626349200cfd6ae8?renderMode=0&uiState=6255db3446b4a5023f0ae595
price: $3.00
quantity:
  standard: 1
  xl: 1
specs:
  Wire Type: 18 AWG stranded copper, two core
  Outer color: Black
  Inner Colors: Red and black
  Heat Shrink color: Black
  connector 1: Black 2-pin connector, Molex Part Number <a href="https://www.molex.com/molex/products/datasheet.jsp?part=active/1510492206_CRIMP_HOUSINGS.xml">151049-2206</a> (prior to July of 2022)<br>Black 2-pin connector, Molex Part Number <a href="https://www.molex.com/molex/products/part-detail/crimp_housings/0050579402">50579402</a> (January 2023 and later)
  connector 2: Pre-stripped wire (no connector)
  length: 10cm
internal-specs:
  internal-part-name: Peripheral Lead
  rev: B
  cost: $1.30
  notes: Kits from production 1 included two Rev A peripheral leads. Due to a connector shortage and subsequent connector change on the Farmduino, kits from production 2 did not include any peripheral leads. Production 3 included Rev B peripheral leads with the new connector.
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Connector and continuity|Connect the lead to a Farmduino and power the peripheral. Use a voltmeter to measure the voltage at the exposed leads.|The cable's connectors should connect as expected and the voltage should be 24V.|N/A
|Length       |Measure the length using a tape measure.|10cm|+/- 1cm
|Cable        |Inspect the cable's spec.|18AWG-2C stranded copper cable|N/A
|Shrinkwrap   |Inspect the color of the shrinkwrap.|Black|N/A
|Color        |Inspect the color of the cable.|Black outer, black and red inner|N/A

{%
include callout.html
type="info"
title="Quantity and connector may vary"
content="Genesis and Genesis XL v1.6 kits shipped before July of 2022 included two peripheral leads with the larger connector. Due to global supply chain disruptions, kits shipped after July of 2022 did not include any peripheral leads. Kits shipped in January 2023 and later included a new revision of the part with a smaller connector."
%}
