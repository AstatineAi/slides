---
title: cs110-review
separator: <!--s-->
verticalSeparator: <!--v-->
theme: simple
highlightTheme: github
css: assets/custom.css
revealOptions:
    transition: 'slide'
    transitionSpeed: fast
    center: false
    slideNumber: "c/t"
    width: 1000
---

<div style="display: flex; justify-content: center; align-items: center; height: 700px;">
  <div style="text-align: center; padding: 40px; background-color: white; border: 2px solid rgb(0, 63, 163); border-radius: 20px; box-shadow: 0 0 20px rgba(0,0,0,0.1);">
    <h1 style="font-size: 48px; font-weight: bold; margin-bottom: 20px; color: #333;">Vending Machine Project Report</h1>
    <p style="font-size: 24px; color: #666;">Phase 1: Requirements</p>
    <p style="font-size: 16px; color: #999; margin-top: 20px;">Hengyu Ai | 2025-04-09 </p>
  </div>
</div>

<!--s-->

<div class="middle center">
  <div style="width: 100%">

  # Part.1 Interface
  
  </div>
</div>

<!--v-->

## Machine Interface

<div style=" margin-top: 10px; margin-right: 50px;" markdown="1">

<img src="images/machine.jpg" width="35%" style="float: right;">

- Panel with serveal hardware
  - Coin insert
  - Cash insert
  - Collect change
  - Return fake coin/cash
  - Keyhole for maintenance
- Case at the bottom
  - Collect goods
- Maintenance interface
  - Available if the machine is open

</div>

<!--v-->

## Screen UI

<div style="margin-top: 10px; margin-right: 50px;" markdown="1">

<img src="images/ui.png" width="40%" style="margin-top: -10px; float: right;">

- The main screen (touch screen)
  - Add/Remove products to cart
  - Clear cart
  - Checkout
  - Display notification
    - Fake coin/cash
    - No merchandise
    - Money not enough
    - ...
  - Show product information
    - Name
    - Price
    - Image

</div>

<!--s-->

<div class="middle center">
  <div style="width: 100%">

  # Part.2 Sensors
  
  </div>
</div>

<!--v-->

## Fake Coin/Cash Sensor

- Activate when inserting coin/cash
- Detects fake coin/cash
  - If detected, report to the main board
  - Return fake coin/cash

<!--v-->

## Product Sensor

- Detects if the product is available
- Activates when the product is selected
- If the product is not available
  - Report to the main board
  - Display notification on the screen

<!--s-->

<div class="middle center">
  <div style="width: 100%">

  # Part.3 Physical Environment
  
  </div>
</div>

<!--v-->

## Coin/Cash Container

- Collects coins/cash
- Fake coin/cash will be returned
- Automatically spits out the corresponding amount of coins/cashes according to the amount of change.
- Only accessible by maintenance personnel

<!--v-->

## Product Storage

- Stores products
- Only accessible by maintenance personnel
- Products are arranged in a grid
  - Each grid has a sensor
  - Product type and information can by modified by maintenance personnel

<!--s-->

<div style="display: flex; justify-content: center; align-items: center; height: 700px;   ">
  <div style="text-align: center; padding: 40px; background-color: white; border-radius: 20px; box-shadow: 0 0 20px rgba(0,0,0,0.1);">
    <div style="display: inline-block; padding: 20px 40px; border-radius: 10 px; margin-bottom: 20px;">
      <h1 style="font-size: 48px; font-weight: bold; margin: 0; color: rgb(16, 33, 89)"> We’re Excited to Partner with You</h1>
    </div>
    <p style="font-size: 24px; color: #666; margin: 0;">🚀 Project Launched 🚀</p>
  </div>
</div>


