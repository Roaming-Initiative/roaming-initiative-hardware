# RITower

This is the main device for creating a mesh backbone that connects devices over long distance, and contains an optional UPS for resistance to utility failure.

## Shopping list

### Required

 * [Aluminum flag pole, such as this one.](http://www.harborfreight.com/20-ft-telescoping-flag-pole-kit-95598.html)
 * [OmniTIK UPA-5HnD wireless omnidirectional router.](http://www.rts-bg.com/product.php?id_product=160)
 * [35-ft CAT6 patch cable, booted](http://www.computercablestore.com/CAT6_Certified_Booted_Net_PID23158.aspx) (This is a minimum size, feel free to go higher if your situation requires).

Total price of these components at the time of this writing, from the sources given: $72.39 + Price of OmniTIK (which you'll probably need to buy via eBay). You can expect to pay around $30 for that, so the whole thing costs about $100.

### Optional

 * UPS, any type designed for 120v plugs.
 * Fiber relay hardware (TBD)
 * [Ubiquiti Nanostation Locos](http://www.ubnt.com/nanostationloco), as many as desired.
 * Multiple 1-2 ft CAT6 patch cables, booted.
 * Extension cord, if necessary.

## Software setup

TODO: instructions for downloading and flashing ADRIS-T on OmniTIK router.

## Hardware setup

### Setting up flagpole

TODO: Write how to install flagpole in stable fashion

### Setting up router

TODO: Write how to attach router to pole

### Hooking up to the ground

Use the long CAT6 cable to run down from the router to the ground. Plug in POE (Power Over Ethernet) doohicky on the free end, and plug *that* into a nearby outlet, using an extension cord if necessary.

You can now test your tower via WiFi with a laptop or other mobile device, or via the ethernet plug exposed by the POE adapter and a small patch cable.
