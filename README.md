
Un sistema di domotica per il controllo energetico domestico con tecnologie open-source.
========================================================================================

#### Progetto di tesi per **Laurea in Informatica**

>(Translated in english: "A home automation system for home energy control with open-source technologies.")

-----------

### The idea

The project is based on the use of various interconnected devices in order to create an home automation system
with the intent of control power consumption of an house. However, this project is a simulation of a larger and directly applicable project.
The house includes the installation of photovoltaic panels, a battery for energy storaging and a DSO (Distribution System Operator).

### The devices

- **Arduino UNO**
- **Raspberry Pi 2**
- **Pulse Counter**
- **A common PC** (<em>with a linux distro installed upon, but it could be done also with other OS</em>)
- **Relay Arduino**
- **Router**
- **Switch**
- **Lamp 100W** (<em>for simulate an energy load</em>)

The code used is written in **Python**, Web Programming languages (such as **Javascript** and **HTML**/**CSS**) and with **Wiring** (the Arduino software development).

####The paper thesis (<em>in italian sorry</em>) is under the `doc` folder, right [here](https://github.com/cbarGit/HomeAutomatProject/blob/master/doc/tesi.pdf).

Every module (*arduino, pc_simulator and rpi*) has his own README file.

So the project is structured like in the image below:

![alt tag](https://raw.githubusercontent.com/cbarGit/HomeAutomatProject/master/doc/logic.png)
