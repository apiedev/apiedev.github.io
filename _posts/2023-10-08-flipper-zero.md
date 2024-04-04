---
layout: post
title:  FlipperZero - Thoughts
categories: [FlipperZero,Hacking,Security]
excerpt: The FlipperZero has been gaining the attention of many security enthusiasts and politicians alike. Many see if as a great tool for penetration testing and finding vulnerabilities in your every day life, while others see it as a threat to society. Here is what I've discovered with mine.
---

### What can it do?

Out of the box the FlipperZero has many features including: Bluetooth, GPIO, Infrared, NFC, RFID, Sub-GHz, USB, iButton, and scripting functions. Immediately I was able to test out the RFID and NFC functions on my work/apt fobs and transport cards. The FlipperZero can easily read, write, and emulate NFC and RFID data with a very reasonable range. 

I quickly changed my focus to the infrared features. I read the IR data coming out of my TV remote when I pressed the buttons, assigned that data to virtual buttons for emulation, and then tried using the FlipperZero as an alternative to my own remote. 
Unfortunately this never worked. Either the FlipperZero sends a very weak IR signal, or my smart TV has a rolling security feature between the IR transmitters and receivers.

The bluetooth functionality can emulate multiple devices out of the box, but nothing that could cause harm. Bluetooth keyboards, mice, and controllers were a few that offered very janky control.

The rest I wasn't able to immediately explore, but upon reading the capabilities, don't see any way it could cause harm immediately out of the box.

### Why are people fearful?

The strength of the FlipperZero comes with its GPIO and scripting capabilities. Put in the hands of someone that knows what they're doing and has intention, it can become a device that make cracking security measures and networks a walk in the park. 

Owners of the FlipperZero can write scripts within C to do virtually anything using the devices onboard functionality. Here is a great video from a pentesting expert showing off its capabilities.

<iframe width="700" height="493" src="https://www.youtube.com/embed/zcshg_2eNJE?si=6sPzkKipavtmB3pe" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Should you get one?

With a steep price point of $170 USD, I wouldn't recommend purchasing a FlipperZero unless you're really interested in how the technology that comes with it works. Its a great little tool to tinker with and get a better understanding of how the world around you functions. But if you expect it to make you a professional hacker overnight, you're better off using the money saved on books that teach you how to do so.