---
layout: page
title: Welcome to ELL-i
header: ELL-i -- Open Source PoE Intelligence -- Home
---
ELL-i is an Open Source hardware and software platform for intelligent
Power-over-Ethernet (PoE) devices.  ELL-i provides both makers and
professionals with open source software, schematics, layouts, and
instructions for designing and building PoE-powered, intelligent, wire
line-communicating devices.  Due to the wire line communication, ELL-i
devices are typically fixed into buildings or embedded into larger,
non-movable things.

An ELL-i Power-over-Ethernet node provides electrical power,
distributed applications, and Ethernet communications at an affordable
price and easy-to-install form factor, thereby allowing a new class of
fixed and embedded devices, such as LED lights, active loudspeakers,
safety systems, sensors, and actuators.

With the Power-over-Ethernet 802.3at standard, utilizing all four
pairs, a single ELL-i node may provide up to 50 Watts of electrical
power over standard Ethernet cabling parallel to data communication
for distributed processing applications.  Given the electrical
capabilities of typical Ethernet cables, we believe that in the near
future it will be possible to deliver up to 100 Watts of power.  Our
long term goal is to extend the ELL-i platform to support also other
types of existing cabling, and even higher amounts of electrical
power.

## Electrical

The Power-over-Ethernet is based on 48V direct current (DC)
electricity, which is ideal for powering modern electrical devices,
such as smartphones, tablets, laptops, or DC current light fixtures,
all of which would normally require a separate AC/DC mains adapter to
provide power for the device.  With ELL-i, a central, efficient AC/DC
converter is used at a PoE switch or hub, converting the mains power
to a 48V direct current.  Close to the actual point of use, an ELL-i
node adapts the 48V to the desired lower voltage; for example, the 5V
used by the USB standard.

The used 48V system is ideal for the maker community, as its
installation does not require any license and at 48V volts one can
provide much more power over existing cables than, for example, at 5V.
The modern DC/DC SMPS power supplies are typically very efficient
(e.g. up to 96-98% with a fixed load); their power losses are very
small.  Overall, an ELL-i system may save up to 30% energy and quite
lot of materials due to the much smaller material consumption of the
DC/DC converters compared to the typical AC/DC adaptors.

## Line

In ELL-i, a single cable is used for transmitting both power and data,
at a very affordable price, providing large savings in cabling
costs.  Each device on the ELL-i network is automatically equipped with
an IP address and access to the Ethernet network, with all of its
usual benefits, including up to 1 Gbps data transmission speeds.
However, we expect that a large majority of the ELL-i applications
will work just fine with the old 10 Mbps Ethernet standard, allowing
us to use readily available inexpensive components.  Compared to the
currently available Ethernet-over-Powerline solutions, the ELL-i nodes
are much smaller and use much less energy.

## Intelligence

Each ELL-i node is equipped with a powerful (48 Mhz) 32-bit
microcontroller.  The microcontroller is available for building
intelligent applications that communicate in real-time with other
nodes, transmit data such as audio or video, and manage autonomously
electrical devices that are coupled with the node.  These applications
are written in C-language and have direct access to intranet and
internet communication services over the same cable that provides
electricity to the microcontroller.

## Platform

Overall, the goal of ELL-i is to create an affordable open platform
that provides 100 Watts of electrical power, 100 Mbps of communication
capacity, up to 100 meters.  The initial CPU provides 48 ARM MIPS, but
we expect this figure to grow to 100 MIPS soon.



