<h1 align="center">Guide on How to Order PCBs from JLCPCB</h1>
This repository provides a detailed step-by-step guide on how to order printed circuit boards (PCBs) from JLCPCB, including file preparation, customization options, and checkout process.

<img src="https://yt3.googleusercontent.com/mzNAZW4JBGk9HfqrtFrhxo2qW52ahd6rktd2CXyKYhaBUPKbE7r55NzvPytmrk-kvxshCn2HRw=s900-c-k-c0x00ffffff-no-rj" alt="JLCPCB Logo" width="100">

## Table of Contents
1. [Step 1: Prepare Your PCB Design Files](#step-1-prepare-your-pcb-design-files)
2. [Step 2: Visit JLCPCB Website](#step-2-visit-jlcpcb-website)
3. [Step 3: Upload Gerber Files](#step-3-upload-gerber-files)
4. [Step 4: Customize PCB Specifications](#step-4-customize-pcb-specifications)
5. [Step 5: Choose Quantity and Lead Time](#step-5-choose-quantity-and-lead-time)
6. [Step 6: PCB Assembly (Optional)](#step-6-pcb-assembly-optional)
7. [Step 7: Confirm Order and Checkout](#step-7-confirm-order-and-checkout)
8. [Step 8: Enter Shipping Details](#step-8-enter-shipping-details)
9. [Step 9: Payment Options](#step-9-payment-options)
10. [Step 10: Track Your Order](#step-10-track-your-order)
11. [Tips for a Successful Order](#tips-for-a-successful-order)

---
## Step 1: Prepare Your PCB Design Files

To order from JLCPCB, you need **Gerber files** containing the PCB design information.

### PCB Design Tools:
- [KiCad](https://www.kicad.org/) - ***I used Kicad for this demonstration.***
- [Eagle](https://www.autodesk.com/products/eagle/overview)
- [Altium Designer](https://www.altium.com/)
- [EasyEDA](https://easyeda.com/)
- [CircuitMaker](https://circuitmaker.com/)

### Generating Gerber Files:
1. Design your PCB in the software.
2. Export or generate Gerber files, ensuring the following layers are included:
   - Top and Bottom Copper
   - Solder Mask
   - Silkscreen
   - Drill File (NC Drill)
3. Compress all files into a `.zip` or `.rar` archive.

WILL ADD photo of Gerber File Generation in KiCad

## Step 2: Got to the JLCPCB Website
1. Go to [JLCPCB’s homepage](https://jlcpcb.com).
2. Click **"Quote Now"** or **"PCB Prototype"**.

## Step 3: Upload Gerber Files
1. Add your `.zip` or `.rar` file into the upload section or click "Upload Gerber File."
2. Review the automatically generated PCB preview.

## Step 4: Customize PCB Specifications
Choose the specifications for the project.

### Customize Options:
1. **Base Material:** FR4 (default) or custom materials.
2. **Layers:** 1 to 6 (or more if needed).
3. **Thickness:** 1.6mm (standard) or other options.
4. **Solder Mask Color:** Green, Blue, Red, Black, etc.
5. **Surface Finish:** HASL or ENIG.
6. **Copper Weight:** 1oz, 2oz, etc.
   
WILL ADD Screenshot of PCB Customization Page

 > ## Optional Suggestion: Consider Ordering a Raw PCB in Addition to an Assembled PCB
 > - Raw PCBs are cheaper than fully assembled ones and useful for early-stage testing of layout, connectivity, and fit.
 > - Engineers can manually add or modify components to test new configurations or make quick changes without waiting for a new assembly.
 > - They serve as backups if assembled boards have defects or misplaced components.
 > - Ideal for students or hobbyists, offering hands-on experience in soldering and component placement.
 > - If components are unavailable from the manufacturer, you can source and solder them yourself.


WILL ADD photo of raw board and Lee's double decker setup

## Step 5: Choose Quantity and Lead Time
- Select **Quantity** (5, 10, etc.).
- Choose **Lead Time** (Standard 2-day production or expedited).


## Step 6: PCB Assembly
Optional, if assembly is needed:
1. Select **SMT Assembly**.
2. Upload BOM and Pick-and-Place files.
   
WILL ADD photo of SMT assembly process 


## Step 7: Confirm Order and Checkout
1. **Review Order Summary:** Ensure all specifications are correct.
2. Triple check all files and order choices.
3. **Add to Cart** and proceed to **Checkout**.


## Step 8: Enter Shipping Details
1. Enter your shipping address.
2. Select the shipping method (DHL, FedEx, etc.).


## Step 9: Payment Options Offered
- PayPal
- Credit/Debit Cards
- Wire Transfer
You will receive an emailed order confirmation.

## Step 10: Track Your Order
1. Track your order status in the JLCPCB dashboard.
2. You will receive tracking info once shipped.

## Tips for a Successful Order
- **Verify Gerber files** using JLCPCB’s Gerber viewer.
- Ensure **BOM** and **PNP** files are accurate for assembly.
- Choose the right **shipping method** based on urgency.
- JLCPCB will inevitably contact you about issues or changes. Triple check your responses and reply as soon as possible to avoid delivery delays.
---

## Contributions
Feel free to contribute improvements to this guide by submitting pull requests or opening issues.

## License
This guide is licensed under the [MIT License](LICENSE).

## Contact 
How to contact me: https://github.com/melanielaporte/ 
