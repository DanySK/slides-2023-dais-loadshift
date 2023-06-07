 
+++

title = "Runtime load-shifting of distributed controllers across networked devices"
description = "DAIS 2023"
outputs = ["Reveal"]

+++


# Runtime load-shifting of distributed controllers across networked devices

## *Danilo Pianini*, Angelo Filaseta

### @DAIS 2023, Lisboa

---

## Problem: centralized monitoring of a distributed system

* image with a dense network (possibly multilevel)
* image of the same network with an observer/administrator
* image of the network with observer observing the whole system
* show a complex rendering on the observer machine
* maybe snapshots from alchemist, with effects. Idea: the realtime controller can be very expensive
* change the monitoring device to a smartphone
* but modern smartphones are powerful, they can render: drain the battery
* state the general problem: the heavy-load part should be moved to the ECC or to the end device at *runtime*
* enough power/battery? render locally. Not enough? Render elsewhere and send a video, send commands away

---

## Analogies

Unsurprisingly, the problem exists in industry as well (videogames)
