<b>Main Idea:</b><br>

  Using a high bandwidth LAN, four cameras, an IMU, and tracking algorithms, a cheap device strapped to an extremity can be used for 6DOF tracking. Instead of using an onboard SOC, taking money, power, and resources, processing will be outsourced to a pc. Whereas a SteamVR plugin will report the tracker’s position.
  
<br>

<b>Constraints:</b><br>

- Needs to be easily attachable to one's leg or foot.
- The tracker needs to be ~50 USD.
- Has to have almost sub-mm precision tracking with consistent reliability.
- Has to be reasonably slim - whilst this is currently subjective and undefined, one should be able to wear it for hours without feeling discomfort.
- The battery should last a considerable amount of time.

<br>

<b>Client:</b><br>

Those in need of a cheap alternative to Vive trackers and lighthouses whilst already owning a PC and headset.
  
<br>

<b>Likely Components:</b><br>

- ESP32-CAM (MCU and wifi module) 
- OV2640 (Camera Module)
- A custom ‘rotating circuit’ of sorts. Requiring three pins on the ESP32-CAM, a plethora of logic gates (XOR, AND, and NOR), and four SRAM modules. 
- A separate 5ghz wifi module (possibly unnecessary)

<br>

<b> Why isn't there a license on this project? </b> <br> 

If this project comes to fruition, I plan on mass-producing the trackers and selling them whilst keeping the project DIY-compatible and the code viewable. Right now, the only way I know how to do that is via the publication of everything I do on a GitHub repo and keeping it under normal copyright law.
<b>I may add one in the future, but for now, it’s not FOSS.</b>

(As far as my knowledge goes, I’m decently sure everything in this project can be forked and edited by the community. That's why I chose this route, you just can't use it for commercial purposes).
