<h1 align="center">Guide on How to Order PCBs from JLCPCB</h1>

This repository provides a detailed step-by-step guide using the Public Invention [MoonRatII](https://github.com/PubInv/moonrat) project and [KiCad](https://www.kicad.org/) as an example on how to order printed circuit boards (PCBs) from JLCPCB, including file preparation, customization options, and checkout process.

<img src="https://yt3.googleusercontent.com/mzNAZW4JBGk9HfqrtFrhxo2qW52ahd6rktd2CXyKYhaBUPKbE7r55NzvPytmrk-kvxshCn2HRw=s900-c-k-c0x00ffffff-no-rj" alt="JLCPCB Logo" width="100">

### PCB Design Software:
- [KiCad](https://www.kicad.org/) 
- [Eagle](https://www.autodesk.com/products/eagle/overview)
- [Altium Designer](https://www.altium.com/)
- [EasyEDA](https://easyeda.com/)
- [CircuitMaker](https://circuitmaker.com/)

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

## Step 1: Prepare Your PCB Design Files in [KiCad](https://www.kicad.org/)

To order from JLCPCB, you need **Gerber files** containing the PCB design information.

1. **Complete Your PCB Design**: Ensure your design is fully completed in KiCad, including all schematics and PCB layout.
2. **Run DRC (Design Rule Check)**: Before exporting, run a DRC to catch any errors that might affect the PCB manufacturing.
file:///Users/melanielaporte/Desktop/Screenshot%202024-09-21%20at%209.44.41%E2%80%AFPM.png
3. **Assign Footprints**: Confirm all components have appropriate footprints assigned.
file:///Users/melanielaporte/Desktop/Screenshot%202024-09-21%20at%209.52.03%E2%80%AFPM.png
file:///Users/melanielaporte/Desktop/Screenshot%202024-09-21%20at%208.23.27%E2%80%AFPM.png
To create an order from JLCPCB, you will need 4 sets of files - Gerber, Drill, BOM, and Drill map.


### Generate Gerbers Files
1. In KiCad, **Open PCB Layout Editor**.
2. Go to `File > Plot` in the PCB layout tool.
   - Choose **Gerber** as the plot format.
   - Select the necessary layers:
     - **F.Cu** (Front Copper)
     - **B.Cu** (Back Copper)
     - **F.Mask** (Front Solder Mask)
     - **B.Mask** (Back Solder Mask)
     - **F.SilkS** (Front Silkscreen)
     - **B.SilkS** (Back Silkscreen)
     - **Edge.Cuts** (Board outline)
   - Select appropriate options for drill files, including through-hole and vias.
   - Click `Plot` to generate Gerber files.
   - Export the files
  
WILL ADD photo of Gerber File Generation in KiCad

### Export Drill Files
   - After plotting, click on the **Generate Drill Files** button.
   - Choose **Excellon** format, and make sure to include **PTH (Plated Through-Hole)** and **NPTH (Non-Plated Through-Hole)**.
     
### Zip the Gerber Files
   - After generating all the Gerber files and drill files, zip them into a single compressed folder. Make sure all necessary layers are included in the zip file.

### BOM file
   -  ADD file creation directions

## Go to the JLCPCB Website
1. Visit JLCPCB**: Navigate to [JLCPCB’s website](https://jlcpcb.com/).
2. **Register or Log In**: If you don’t have an account, create one. If you do, simply log in.

## Step 3: Upload Gerber Files
1. On the JLCPCB homepage, click the **“Order Now”** button under the PCB manufacturing section.
2. **Upload the ZIP File** containing your Gerber files.
3. JLCPCB will automatically analyze the files and present you with a preview of your board.

## Step 4: Configure PCB Options
1. Review the auto-generated preview to ensure it matches your design.
2. Customize the PCB:
   - **Dimensions**: This should be automatically detected from the Gerber files.
   - **Layers**: Typically 2-layer or 4-layer, depending on your design.
   - **Quantity**: Choose the number of PCBs you need.
   - **Thickness**: Common options are 1.6mm, but you can choose different thicknesses depending on your needs.
   - **Solder Mask Color**: Green is standard, but other colors are available.
   - **Silkscreen Color**: White is typical.
   - **Surface Finish**: Choose between HASL (Lead/Lead-Free) or ENIG (Gold).

   
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
