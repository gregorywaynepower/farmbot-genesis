---
title: "Motor"
slug: "motor"
description: "These powerful 200 resolution stepper motors allow FarmBot to move precisely in the X, Y, and Z directions. Download the [motor spec sheet](https://drive.google.com/file/d/1Ehqu20q84Lyycn1fOj6dvWKbrMLvoNv4/view?usp=sharing) and [encoder spec sheet](https://drive.google.com/file/d/15dSqr_hQTXAQGIvw-YeDLIOC6dB0Y26n/view?usp=sharing)."
cad: https://cad.onshape.com/documents/728fa8fdb342a040fe0ca4b5/w/0435033a7c78b02e71d0f721/e/721ea5b310ba257b355c62ae?renderMode=0&uiState=6255db2446b4a5023f0ae580
price: $70.00
quantity:
  standard: 4
  xl: 4
specs:
  motor resolution: 200 steps/revolution (1.8 deg/step)
  winding type: Bipolar
  voltage: 12V
  current draw: 1.68A max
  shaft diameter: 5mm diameter
  mount hole pattern: 4x M3 holes, standard NEMA 17 pattern
  motor connector: 6-pin connector (only 4 pins used)
  encoder connector: 8-pin connector
  encoder resolution: 360 lines/revolution
  encoder output: Differential
internal-specs:
  internal-part-name: NEMA 17 Stepper Motor w/ Rotary Encoder
  vendor: Motor - LDO<br>Encoder - Honest Sensor
  cost: $33.90
  notes: "<span style='font-weight: bold; color: red;'>Logo engraving must NOT be stretched.</span> Please send photo of first samples to verify.<br>Insert into motor box with FarmBot logo facing DOWN."
---

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Motor length |Measure the length of the motor body (no encoder or shaft) using digital calipers.|47.3mm|+/- 0.5mm
|Motor housing fit|Mount a motor to the cross-slide plate with a horizontal motor housing.<br><br>Mount a motor to the z-axis motor mount and cover with the vertical motor housing.|Motor should fit inside housing|N/A
|Shaft        |Mount a GT2 pulley onto the motor shaft according to the FarmBot system design.|Pulley should mount as expected|N/A
|Shaft length |Measure the length of the motor shaft using digital calipers.|22mm|+/- 0.5mm
|Mounting holes|Mount a motor to a cross-slide plate according to the FarmBot system design.|Screws should thread into motor as expected|N/A
|Motor operation|Connect the motor to a Farmduino and issue a movement command.|Motor should operate as expected|N/A
|Encoder      |Connect the motor and encoder to a Farmduino, issue a movement command, and inspect the encoder position in the web app.|Encoder position values should update as expected|N/A
|Engraving    |Inspect the FarmBot logo engraving.|Must not be stretched|N/A
