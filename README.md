# Outlet-Automation
An Arduino device that controls an outlet

I realized I didn't like having to remember what times to turn my fisthtank lights on or off, so I created this device to do it for me and save me the arduous task of flipping a small lever.
It works by using an RTC to tell the time to the Arduino, which then takes the hour into account and turn the light on or off depending on the time.
This is done by sending a signal to a relay, which is connected to a standard power outlet.
This means that if the lights for the aquarium are plugged into the outlet, they only receive power when the relay completes the circuit.

I've also attached pictures of my initial breadboard setup, the schematic, and the code I used.
