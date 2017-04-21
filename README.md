# Enhanced-Dimmer-Switch
Smartthings Dimmer Switch Device Handler. Allows customization of switch's behavior. I use it for my GE Z-Wave Plus Smart Dimmer (In-Wall), 14294 switches.

# Usage
Open up the device configuration menu (the Gear Icon).  Choose settings that you like.  The settings will be pushed to the device when you exit the settings menu.

## Hints

For instant on set Steps in Percent to 99.

My LED lights seem to like 3% or 5% steps. With a 10 to 20 delay between.

# Install

#### With GitHub Integration

 * Go to My Device Types in the IDE
 * Click on **Settings**
 * Click on **Add new repository**
 * Owner: desertblade, Name: Enhanced-Dimmer-Switch, Branch: master
 * Under My Device Types Click on Update from Repo and select the *Enhanced-Dimmer-Switch*
 * Check the box next to Enhanced-Dimmer-Switch
 * Check the box for **Publish**
 * Click **Execute** Update
    
    
#### The Manual Way
 * Go to "**My Device Handlers**"
 * Create "**New Device Handler**"
 * Choose "**From Code**"
 * Copy Source code from *enhanced-dimmer-switch.groovy*
 * Remember to open each device and click "**Publish**" and "**For me**"
 
# Change Device Handler
Once installed you will need to change you device to use this handler.

 * Go to "**My Devices**" in the IDE
 * Click on the switch you want to modify
 * Click **Edit** Button
 * In "**Type**" Filed choose **Enhanced Dimmer Switch**
 * Click **Save**
 * Goto the device on you mobile device
 * Modify settings in Prefrences
 * Click Configure
 
 

