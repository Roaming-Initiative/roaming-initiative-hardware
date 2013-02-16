# RITower

This is the main device for creating a mesh backbone that connects devices over long distance, and contains an optional UPS for resistance to utility failure.

## Shopping list

### Required

 * [Aluminum flag pole, such as this one.](http://www.harborfreight.com/20-ft-telescoping-flag-pole-kit-95598.html)
 * [OmniTIK UPA-5HnD wireless omnidirectional router.](http://www.rts-bg.com/product.php?id_product=160)
 * [35-ft CAT6 patch cable, pre-crimped](http://www.computercablestore.com/CAT6_Certified_Booted_Net_PID23158.aspx) (This is a minimum size, feel free to go higher if your situation requires).

Total price of these components at the time of this writing, from the sources given: $72.39 + Price of OmniTIK (which you'll probably need to buy via eBay). You can expect to pay around $30 for that, so the whole thing costs about $100.

### Optional

#### Recommended
 * UPS, any type designed for 120v plugs.
 * Multiple 1-2 ft CAT6 patch cables, preferably pre-crimped.
 * Extension cord, if necessary.


#### Handy to have
 * Fiber relay hardware (TBD)
 * [Arc Wireless FreeStations](http://www.antennas.com/freestation/) or [Ubiquiti Nanostation Locos](http://www.ubnt.com/nanostationloco), as many as desired.
 * Additional band clamps, if necessary (probably a good idea, and a necessity if your hardware doesn't ship with them)

## Software setup

TODO: instructions for downloading and flashing ADRIS-T on OmniTIK router.

## Hardware setup

### Setting up flagpole

Multiple options are available for setting up a flagpole such as the one listed above. You can either pound the included mounting tube into the ground & set the flagpole into that, or you could band clamp it to a fence or secure it to a roof.

### Setting up router

The Omnitik includes a band clamp & mounting bracket for poles & other cylindrical objects. Just mount the Omnitik to the pole using the included parts, as they work well for the task & are compatible with the pole. Make sure to skip mounting the included brass ball on the top of thepole, as it blocks other radios from seeing a good chunk of the Omnitik's antenna.

### Hooking up to the ground

Use the long CAT6 cable to run down from the router to the ground. Plug in the POE (Power Over Ethernet) injector on the ground end of the ethernet cable, and plug *that* into a nearby outlet, using an extension cord if necessary.

You can now test your tower via 5ghz WiFi with a laptop or other mobile device, or by plugging in to the Omnitik using the tail end of the POE injector. 

## Hardware Modifications

### Omnitik DIY POE out

With this modification you can add POE out on all 4 ethernet ports that are available for other devices to plug into on your Omnitik. Check out a [completed POE out mod](http://www.flickr.com/photos/h2non/sets/72157627860401917/) & try it yourself.
