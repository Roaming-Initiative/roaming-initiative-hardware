# RITower

This is the main device for creating a mesh backbone that connects devices over long distance, and contains its own UPS for resistance to utility failure.

The RITower design is a simple aluminum pole, of variable height, with specific components at the top and bottom. These are respectively known as the head and base areas.

## Head

The head contains all IP infrastructure. It is powered by an extension cord of suitable length that terminates in a power strip with 5+ outlets.

### WiMax Basestations

 * Preferred brand TBD.
 * Enough to provide omnidirectional coverage.
 * Weatherproof.
 * Connected to switchbox via CAT6.
 * Each runs its own instance of CJDNS.

### Omnidirectional WiFi router

 * Preferred brand TBD.
 * Provides WiFi access point or ad hoc coverage for consumer mesh hardware.
 * Weatherproof.
 * Connected to switchbox via CAT6.
 * Runs its own instance of CJDNS.

### Switchbox

 * Sealed tupperware container, which holds high-speed switch and power strip.
 * For ethernet and power cables, holes should be drilled, and the cables sealed in airtight with silicone.

### Switch

 * 4+ ports, depending on how many WiMax devices are being used.
 * Connects all WiMax devices and WiFi router together, filtering communication such that each device only gets traffic to or from its IP addr.

### Power Strip

 * Connects to the end of the extension cord.
 * Should have an outlet for every device: router, switch, and one per basestation.

## Pole

 * Method of attaching devices and switchbox to pole TBD.

## Base

Has a UPS for utility failure resistance.

### UPS

 * Any brand acceptable.
 * Accepts and delivers AC power.
 * Supplies extension cord that runs up the pole.
 * May be ommitted for non-critical or test stations. Should be used for real infrastructure.
 * Protect from elements with industrial pallet below, and a tarp on top, bungie-tied to the pallet.

### Attachment to the ground

 * Should either be with 2ft of concrete, or wide flat base.
 * To set up with concrete:
    * Dig hole 6-12 inches in diameter.
    * Place small brick at the bottom.
    * Put pole on top of that.
    * Stabilize and level pole.
    * Pour quick-setting concrete mix into the hole around the pole, leaving about 2 inches free at the top.
    * Pour in water, use stick or rebar to mix and tamp concrete.
    * Repeat the last two steps for the final 2 inches.
    * Allow dry time according to concrete mix instructions. Expect at least one day before treating the pole as stable.
 * For mobile base:
    * Find large piece of plywood, plastic, or metal.
    * Bolt it together with the pole using large L-brackets.
    * Weigh down with rocks/chunks of concrete.
    * This method is fast and mobile, but also at much higher risk of wind damage.
