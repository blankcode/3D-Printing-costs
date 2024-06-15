
# 3D-Printing-costs (FDM / FFF)
**Warning**: Changing SHEETNAMES or cell positions will break most of the formulas in this workbook. 

If you have ideas about something to add, please let me know since I'd probably like to use it to.
## Quote
Your shop's product's Quote

Click on the Description > Select Part > Part Quote is displayed

## Parts
Your shop's products list. For each part fill in the feilds. 

Weight (g) and Print Time (2 days, 3 hours, 5 Minutes enter as 51:05 / 52 Mins enter as 0:52) from your slicer. 

The next 7 fields are in minutes it takes to perform the action. 

Quote Price is how much you want for the part. The purple fields are just for notes. 

Hardware fields: Select via dropdown the intented hardware and input a count of them to the right.

## Client Quote
One off parts/project quote. Same as "Quote", but isolated.

## Client Parts
One off parts/project List. Same as "Parts", but isolated.

## Hardware|Consumables
Hardware that is added to your parts.

A list of hardware their costs, cost per unit, and where to get them.

## Printers
Your printer Models, not individual machines. (*I have four Sovol SV06+ printers, ZI list one printer.*)

**Input**: Name, Material Diameter [mm], Price, Depreciation Time, Service costs per life, Energy Consumption [kWh/h], Start-Up Time

## Materials
Your materials. This is where the pricing for your material resides.

## General
General Variables

**Input**: Energy cost, High Labor Costs, Low Labor Costs, Failure rate, Money unit, Payment processing costs

**For Space Input**: Rent/Mo, Tot. Sq. Ft., Used Sq. Ft.

## Inventory Management
In these 4 sheets, I have each of the colors I use denoted with a color name and a background color representative of the color.

### Product Inventory
Each product (line) has a list of colors, and each color has 3 numbers:
 - Printed parts in inventory ready to sell.
 - How many printed parts do you want in inventory.
 - Parts that are needed to be printed to fill inventory.

Overstocks are shown as negatives

### Materials Inventory
Inventory of individual rolls of filament.
