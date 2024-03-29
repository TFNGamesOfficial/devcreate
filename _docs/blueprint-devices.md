---
name: Blueprint Devices
tools: [Recently added, Device, Island]
image: https://www.epicgames.com/fortnite/en-US/creative/docs/Images/using-accolades-devices-in-fortnite-creative/accolade-device-hero.png
description: Help players earn Season Pass and Laboratory Pass XP using the Accolade device.
---

![Accolade](https://images-ext-1.discordapp.net/external/o6XlHS-LeGoSxkoy-wBaabe44FOIbFz49nycfm8tfug/https/www.epicgames.com/fortnite/en-US/creative/docs/Images/using-accolades-devices-in-fortnite-creative/accolade-device-hero.png?width=1200&height=343)
# ACCOLADE DEVICE
With the **Accolade** device, you can set up your islands so players will earn Battle Pass XP when they interact with your island. Accolades are achievements or accomplishments that players can complete to earn XP.

There is a sample island that includes multiple accolades, which you can visit to see how they work. The island code for this sample island is **2034-7205-6925**. To play through this island, from the Creative lobby click CHANGE to open the Discover screen. Click the **CODE** tab, then enter the island code for the sample Accolades island in the box and press Enter. The window will display information about the island. Click **PLAY** to launch the game.

In general, the Accolade device is designed to work with other devices, and players can't interact with it directly. To grant XP to your players, other devices must send signals to the Accolade device when the players do certain things.

**NOTE:** The Accolade device takes very little memory. The first Accolade device placed uses 88 memory; each one placed after the first uses 8 memory.

# UNDERSTANDING XP AWARD WEIGHTS
When you place an Accolade device, you are able to set the XP Award amount to Very Small, Small, Medium, Large, and Very Large. The amount is not a set amount of XP. Instead it is weighted. This means a different amount is granted depending on a set of criteria. This happens in the background and is not something creators can customize.

The amount of XP granted is based on how many Accolade devices you have on your island plus how frequently an accolade is awarded. High-frequency accolades result in smaller XP amounts. Low frequency accolades result in higher XP amounts. For example, if you have an accolade with a Very Large XP Award and high award frequency, and you have an accolade with a Very Small XP Award with low award frequency, then the Very Small Award may actually give more XP to a player than the Very Large Award.

When you set up your accolades, think about the complexity of the accolade and how often it can be achieved. This will help you determine what XP Award weight is appropriate for that accolade.

When your island is published, it will go through a calibration process to evaluate how often players receive each accolade compared to how long they play. The calibration system requires a number of play sessions over time in order to make the calculations it needs to accurately calibrate the island. Once calibration is complete, the weights for each level of XP award are determined.

**NOTE:** If you edit your island and adjust the XP Award option in the Accolade devices, you will need to republish your island so it can be recalibrated.

### CONTEXTUAL FILTERING
Some devices are affected by a feature called contextual filtering. This feature hides or displays options depending on the values selected for certain related options. This feature will reduce clutter in the Customize panel and make options easier to manage and navigate.

However, it may not be easy to recognize which options or values trigger contextual filtering. To help you identify them, in our device docs we use italic for any values that trigger contextual filtering. All options will be listed, including those affected by contextual filtering; if they are hidden or displayed based on a specific option's value, there will be a note about that in the Description field for that option.

### DEVICE OPTIONS
Basic options provide a way to name, describe and weight your awards. Other options control visibility, how the device is triggered, and who can trigger it.

You can configure this device with the following options.

<table>
  <tr>
    <th>Setting</th>
    <th>Value</th>
    <th>Value (V2)</th>
    <th>UE4.28-TxE Values</th>
  </tr>
  <tr>
    <td>Setting 1</td>
    <td>Value 1</td>
    <td>Value (V2) 1</td>
    <td>UE4.28-TxE Values 1</td>
  </tr>
  <tr>
    <td>Setting 2</td>
    <td>Value 2</td>
    <td>Value (V2) 2</td>
    <td>UE4.28-TxE Values 2</td>
  </tr>
  <tr>
    <td>Setting 3</td>
    <td>Value 3</td>
    <td>Value (V2) 3</td>
    <td>UE4.28-TxE Values 3</td>
  </tr>
</table>

