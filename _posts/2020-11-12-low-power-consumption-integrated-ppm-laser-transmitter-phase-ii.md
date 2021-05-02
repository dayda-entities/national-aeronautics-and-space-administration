---
title: Low-Power-Consumption Integrated PPM Laser Transmitter, Phase II
created: 2020-11-12T04:24:53.487175
modified: 2020-11-12T04:24:53.487186
state: active
type: dataset
tags: dataset
groups: dataset
csv_url: 
json_url: 
published: true
---
Conventional PPM laser transmitters, a CW laser followed by a modulator, are inherently inefficient since the data must be carved from the laser's steady output.  95% of the optical power is discarded in a standard telecom RZ format, with another 8x efficiency reduction using a PPM scheme. An alternative is to form the pulse train with a mode-locked laser. However, since the resultant MLL pulse train is periodic, it must produce pulses in every symbol slot, not just once per symbol.  This means that for a 32-ary PPM scheme, the MLL optical efficiency is reduced by a factor of at least 32 by discarding the un-needed pulses.  In both cases, the electro-optic modulator itself induces an additional 60% optical loss, and requires nearly 0.5W of power to drive.  An alternative is to use a low-repetition-rate MLL in combination with a switch fabric to delay each output pulse into the correct PPM slot.  However, the use of photonic integrated circuits (e.g., silicon) is prohibitive due to the high intrinsic loss.  A 100-MHz PPM data rate scheme requires ~5ns pulse delay.  This represents 43-cm propagation in silicon, inducing a power loss over 10 dB.  Adding the loss due to spiraled delay lines, switch junctions, and coupling on/off chip, the aggregate loss of the switch fabric is 18 to 24 dB, representing a significant efficiency loss.  RAM Photonics proposes the development of a qualitatively novel approach to high-efficiency, low-bit-rate laser transmitters compatible with space-borne missions.  Specifically, we propose to develop a laser transmitter that attains highly efficiency optical data generation by (1) generating only one optical pulse per symbol at arbitrary temporal location, (2) eliminating all electro-optic modulators, and (3) exploiting new advances in fiver optic and opto-electronic packaging.  The new transmitter device has low dissipation (< 0.5 W total) and low SWaP footprint, and can operate at arbitrary data rates and generate any symbol formats.
