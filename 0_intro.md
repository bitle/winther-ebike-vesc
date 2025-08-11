# Introduction

I recently bought a used Winther Cargo e-bike off of Facebook Marketplace. It was sold cheaply with damanged connector. I eventually found out that it was the display connector.
As I kept playing with this e-bike I learned a lot of things about the controller, e-bike controllers in general and some cool new things in this space. My goal here is to document the knowledge that I gained about this e-bike system and document the journey of converting this old e-bike to VESC.

## How it all started
As I said, I bought this used Winther Cargo e-bike on Facebook Marketplace. The seller stated that it stopped working one day and the pictures showed one damaged cable connector. I figured I'll replace the connector and the bike will start working again. This assumtion turned out to be almost completely correct. I replaced the cable and the bike became functional again, not 100% functional as I hoped but ridable.

## Initial investigation
I came to all of this with near zero knowledge about ebikes. I know there is a controller, a battery, a motor and a pedal assist sensor, but I didn't know much beyond this. So I have this ebike that doesn't turn on. First I needed to identify the cable that is damaged. Luckily, the controller has easily detachable cables. This allowed me to disconnect all cables and inspect them. One cable clearly was missing two pins and I could see those pins stuck inside the controller. At this point I had three options:
* identify what this cable is responsible for and replace the part
* solder the wire directly to the board
* replace the connector

With some help from Google Gemini I was able to identify that this is a Juliet cable connector. It seems to be pretty standard in ebike world. Then by pulling the wires I figured out that this connector is for ebike display with on/off switch and assist level selection. At this point I had all information that I needed to move forward. I found compatible 6 pin Juliet cable on AliExpress and I had an option of soldering the wire in my back pocket. I dismissed the option of buying a replacement display, because that's boring. I wanted a fun project to learn.
