# LEO1s Upgrade Note

It has not been that long ago since we released **LEO** , you know the date **2019/10/21**. Since then many  people  help us to make LEO better, tell us what should be better and stable. And with urge to improve and upgrade and efforts to make , finally we reach this milestone : LEO1s.

So let me introduce you to our newest HiPrecy machine, the **HiPrecy LEO1s **. It looks very familiar, but many parts are **new and improved**. Don’t be deceived by the familiar look! Let's take a look at new features.

![](images/LEO1s.jpg)

## New features

- **Marlin 2.0.x support**
- **New UI Theme : Dark theme**
- **Accurate probe**
- **Stronger Magnetic Heatbed**
- **Stronger Stepper Driver - TMC2209**
- **E3D V6 Hotend block**
- **New Anti-Slip Belt and guide wheel**
- **New cooling fan**
- **Extruder Brace and Heated bed Wire Guide**

## New UI Theme

LEO1s  have two UI theme for you to choose. Which one do you prefer ?

| Light Theme                | Dark Theme                |
| -------------------------- | ------------------------- |
| ![](images/LightTheme.jpg) | ![](images/DarkTheme.jpg) |

## Accurate probe

Obviously , you can see the differences from the pictures below. The cable of new probe is much stronger than the old one. This ensure the printer gets stable and accurate signal from the probe.   And the new one support S6 board but old one not.

![](images/Probe.jpg)



## Stronger Magnetic Heatbed

We add more magnet to have stronger magnetism hold the plate. So plate won't move even you print a large model. 

| Old                         | New                         |
| --------------------------- | --------------------------- |
| ![](images/Heatbed-old.png) | ![](images/Heatbed-new.png) |



## Stronger Stepper Driver - TMC2209

Why we choose TMC2209 in the end? Let's check their parameter

| Item              | TMC2130                                            | TMC2209                                            |
| ----------------- | -------------------------------------------------- | -------------------------------------------------- |
| Model             | <img src="images/TMC2130.jpg" style="zoom:32%;" /> | <img src="images/TMC2209.jpg" style="zoom:30%;" /> |
| Phase Current max | 1.2A                                               | 1.7A                                               |

So , there are two benefits to have a larger max current. First obviously , it has more power to drive the stepper motor , so we can print faster. Second , when we print the same model at same speed , TMC2209 won't generate so much heat , so it can print a longer time. And with little heat , it works in a better condition , so we can get a better print. 

## E3D V6 Hotend Block and New Thermistor

| Item       | Old                            | New                            |
| ---------- | ------------------------------ | ------------------------------ |
| Hotend     | ![](images/Hotend-old.jpg)     | ![](images/hotend.jpg)         |
| Thermistor | ![](images/Thermistor-old.jpg) | ![](images/Thermistor-new.jpg) |

E3D V6 Hotend Block and the new thermistor. I think you already know the advantage of E3D hotend , and the head of the new thermistor is covered with cap , makes it safe and easy to install to the hotend. And it will be stable after the screw is tightened up. 

## New Anti-Slip Belt and Guide Wheel

| Old                      | New                      |
| ------------------------ | ------------------------ |
| ![](images/Belt-old.jpg) | ![](images/Belt-new.jpg) |

The new belt is High Quality , Low Dust, Low Vibration, high-accuracy belt. It helps the printer to have more accurate movement.  

<img src="images/RoughEdge.jpg" style="zoom:20%;" />

As you can see above, the guide wheel fringed edge may annoy you. Don't worry , To the greatest extent, our new guide wheel avoid the occurrence of this kind of issue.

## New cooling fan

This time we try to lower down the noise of the machine. So we change all the fans to Dual ball bearing fans.

<img src="images/fans.jpg" style="zoom: 15%;" />

## Extruder Brace and Hotbed wire Guide

Thanks Junior Barnes and Johnny Baier for their share. We adopted Extruder Brace from Johnny Baier and hotbed wire guide from Junior Barnes. You can find them with the link.

|                   | Junior Baier                                             | Junior Barnes                                                |
| :---------------- | -------------------------------------------------------- | ------------------------------------------------------------ |
| Extruder Brace    | <img src="images/extruder-new.jpg" style="zoom:150%;" /> | <img src="images/ExtruderHotendBrace.jpg" style="zoom:80%;" />https://www.thingiverse.com/thing:4168784?fbclid=IwAR1Fr12TrfkQYR64NMfzh2RNe0PM1c7bJcJ8YfDncZT212WxogndVcAQWT8 |
| Hotbed wire guide |                                                          | ![Hiprecy](images/HeatedBedWireGuide.jpg)https://www.thingiverse.com/thing:4337602?fbclid=IwAR1UR9UriQtYRVJeR3zQx-7aI9rOhrsCmv7g2zMI6kIQ52LqliTlLejkgiA |

## Comparison Table

| Items               | LEO          | LEO1s                 |
| ------------------- | ------------ | --------------------- |
| Build volume        | 230x230x260  | 230x230x260           |
| Layer height        | 0.05mm-0.2mm | 0.05mm-0.2mm          |
| Speed               | 3600mm/min   | 5400mm/min            |
| PSU                 | 110~220V/24V | 110~220V/24V          |
| PowerPanic          | Yes          | Yes                   |
| Motherboard         | FYSETC F6    | FYSETC F6             |
| Bontech gears       | Yes          | Yes                   |
| Hotend fan          | Normal       | Dual ball bearing fan |
| Print fan           | Normal       | Dual ball bearing fan |
| Drivers cooling fan | Normal       | Dual ball bearing fan |
| Probe               | Normal       | Accurate              |
| Pulley              | Normal       | Wear-resistant        |
| Belt                | Normal       | Anti-slip Belt        |
| Hotbed              | 23 magnets   | 31 magnets            |
| Hotend block        | Normal       | E3D V6                |
| Thermistor          | NTC3950      | Shell NTC100k         |
| Extruder brace      | No           | Yes                   |
| Trinamic drivers    | TMC2130      | TMC2209               |
| Marlin version      | 1.1.x        | 2.0.x                 |
| UI Theme            | Light        | Light/Dark            |

## Optional Accessories

In addition to all these , we also support Bltouch , Seal hotend , and of course OctoPrint.

### Bltouch Support

You can follow [the guide book of how to install](https://github.com/HiPrecy/Product-Information-LEO/tree/master/2.User's%20Guide/3DTouch-Bltouch%20Installation "With a Title"). 

![](images/Bltouch.png)

### Seal Hotend

You can follow [the guide book of how to install](https://github.com/HiPrecy/Product-Information-LEO/tree/master/2.User's%20Guide/Seal%20hotend%20Installation "With a Title"). 

<img src="images/SealHotend.jpg" style="zoom:70%;" />

### OctoPrint support

This is from our facebook member , he install a octoprint screen and you can find the link here:

https://github.com/Z-Bolt/OctoScreen?fbclid=IwAR2pvfAnHtc-zwsDn4AuRyLIHDU9qf4ri2ESI6BsBVXwVQrhx8JxUeIzElY

- ![](images/octoprint.jpg)