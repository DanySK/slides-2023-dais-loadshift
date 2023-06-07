
+++

title = "Runtime load-shifting of distributed controllers across networked devices"
description = "DAIS 2023"
outputs = ["Reveal"]

+++

{{%
    slide background-image="https://raw.githubusercontent.com/DanySK/shared-slides/6824b93d3d52b841386a744f57953a73ccb67378/backgrounds/dark-net-dots.png"
    transition="slide"
    preload="true"
%}}

# Runtime load-shifting of distributed controllers across networked devices

## *Danilo Pianini*, Angelo Filaseta

### @DAIS 2023, Lisboa

---

{{%
    slide background-image="test.gif"
    transition="fade"
    preload="true"
%}}


---

{{%
    slide background-image="test.gif"
    transition="fade"
    preload="true"
%}}

<i class="fa-solid fa-arrow-right" style="
  color: #333;
  font-size: 5em;
  position: absolute;
  top: 400px;
  left: 875px;
  transform: rotate(20deg);
"></i>

<div style="
  position: absolute;
  top: 300px;
  left: 600px;
  width: 250px;
  height: 200px;
  border-radius: 40px;
  border: 5px solid #333;
  background: #008c3199;
"></div>

<div style="
  position: absolute;
  top: 400px;
  left: 1000px;
  height: 400px;
  width: 550px;
">

![](try-hack.png)

</div>

---

{{%
    slide background-image="test.gif"
    transition="fade"
    preload="true"
%}}

<i class="fa-solid fa-arrow-right" style="
  color: #333;
  font-size: 5em;
  position: absolute;
  top: 320px;
  left: 1170px;
  transform: rotate(70deg);
"></i>

<div style="
  position: absolute;
  top: 50px;
  left: -150px;
  width: 1300px;
  height: 800px;
  border-radius: 40px;
  border: 5px solid #333;
  background: #008c3199;
"></div>

<div style="
  position: absolute;
  top: 400px;
  left: 1100px;
  height: 400px;
  width: 550px;
">

![](try-hack.png)

</div>


---

{{%
    slide background-image="test.gif"
    transition="fade"
    preload="true"
%}}

<i class="fa-solid fa-arrow-right" style="
  color: #333;
  font-size: 5em;
  position: absolute;
  top: 320px;
  left: 1170px;
  transform: rotate(70deg);
"></i>

<div style="
  position: absolute;
  top: 50px;
  left: -150px;
  width: 1300px;
  height: 800px;
  border-radius: 40px;
  border: 5px solid #333;
  background: #008c3199;
"></div>

<div style="
  position: absolute;
  top: 400px;
  left: 1100px;
  height: 400px;
  width: 550px;
">

![](try-hack.png)

</div>

<div style="
  position: absolute;
  top: 475px;
  left: 1210px;
  height: 400px;
  width: 100px;
">

![](mac-loading-icon-0.jpg)

</div>


<div style="
  position: absolute;
  top: 70px;
  left: 150px;
  height: 400px;
  width: 700px;
">

![](mac-loading-icon-0.jpg)

</div>

---

{{%
    slide background-image="test.gif"
    transition="fade"
    preload="true"
%}}

<i class="fa-solid fa-arrow-right" style="
  color: #333;
  font-size: 5em;
  position: absolute;
  top: 320px;
  left: 1170px;
  transform: rotate(70deg);
"></i>

<div style="
  position: absolute;
  top: 50px;
  left: -150px;
  width: 1300px;
  height: 800px;
  border-radius: 40px;
  border: 5px solid #333;
  background: #008c3199;
"></div>

<div style="
  position: absolute;
  top: 400px;
  left: 1100px;
  height: 400px;
  width: 550px;
">

![](try-hack.png)

</div>

<div style="
  position: absolute;
  top: 475px;
  left: 1210px;
  height: 400px;
  width: 100px;
">

![](mac-loading-icon-0.jpg)

</div>


<div style="
  position: absolute;
  top: 70px;
  left: 150px;
  height: 400px;
  width: 700px;
">

![](mac-loading-icon-0.jpg)

</div>

<div style="
  position: absolute;
  top: 405px;
  left: 1380px;
  height: 400px;
  width: 173px;
">

![](worried-vault-boy.png)

</div>

---

{{%
    slide background-image="test.gif"
    transition="fade"
    preload="true"
%}}

<div style="
  position: absolute;
  top: 50px;
  left: -150px;
  width: 1300px;
  height: 800px;
  border-radius: 40px;
  border: 5px solid #333;
  background: #008c3199;
"></div>

<div style="
  position: absolute;
  top: 570px;
  left: 850px;
  height: 800px;
  width: 900px;
">

![](hacker.png)

</div>

---

{{%
    slide background-image="test.gif"
    transition="fade"
    preload="true"
%}}

<div style="
  position: absolute;
  top: 50px;
  left: -150px;
  width: 1300px;
  height: 800px;
  border-radius: 40px;
  border: 5px solid #333;
  background: #008c3199;
"></div>

<div style="
  position: absolute;
  top: 570px;
  left: 850px;
  height: 800px;
  width: 900px;
">

![](hacker.png)

</div>

---

{{%
    slide background-image="test.gif"
    transition="fade"
    preload="true"
%}}

<div style="
  position: absolute;
  top: 50px;
  left: -150px;
  width: 1300px;
  height: 800px;
  border-radius: 40px;
  border: 5px solid #333;
  background: #008c3199;
"></div>

<div style="
  position: absolute;
  top: 570px;
  left: 850px;
  height: 800px;
  width: 900px;
">

![](hacker.png)

</div>

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

{{%
    slide background-image="https://raw.githubusercontent.com/DanySK/shared-slides/6824b93d3d52b841386a744f57953a73ccb67378/backgrounds/dark-net-dots.png"
    transition="slide"
    preload="true"
%}}

## Analogies

Unsurprisingly, the problem exists in industry as well (videogames)
