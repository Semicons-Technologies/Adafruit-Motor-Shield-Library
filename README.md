# SEMICONS TECHNOLOGIES

> ### A platform that provides and offers innovative thinkers or individuals, the necessary tools and knowledge to bring their imaginations to life.

---

**Date Modified:** 18th November 2020  
**Website:** [www.semicons.tech](www.semicons.tech)

- [Academy](www.semicons.tech/academy)
- [Community](www.semicons.tech/community)
- [Online Store](www.semicons.tech/store)
- [Semicons Kits](www.semicons.tech/semicons-kits)

---

# Adafruit Motor Shield Library

This library is old and deprecated - and the hardware disconinued years ago. V2 of the shield uses i2c only and works with anything that has I2C support (e.g. all arduinos) without endless incompatibilities and porting requirements! :)
-> https://www.adafruit.com/products/1438

---

This is the August 12, 2009 Adafruit Motor shield firmware with basic Microstepping support. Works with all Arduinos and the Mega
Updated in September 2012 for use on PIC32 architecture (chipKIT/MPIDE)

For more information on the shield, please visit https://learn.adafruit.com/adafruit-motor-shield

To install, click DOWNLOAD SOURCE in the top right corner, and see our tutorial at http://www.ladyada.net/library/arduino/libraries.html on Arduino Library installation

---

To use

```c
#include <AFMotor.h>

AF_DCMotor motor(4);
motor.run(RELEASE);
motor.setSpeed(i);
```

# Syntax Coloring Map for AFMotor

## Datatypes (KEYWORD1)

```c
AF_DCMotor	KEYWORD1
AF_Stepper	KEYWORD1
```

## Methods and Functions (KEYWORD2)

```c
run	      KEYWORD2
step	  KEYWORD2
enable	  KEYWORD2
onestep	  KEYWORD2
release	  KEYWORD2
setSpeed  KEYWORD2
```

## Constants (LITERAL1)

```c
BRAKE	        LITERAL1
SINGLE	        LITERAL1
DOUBLE	        LITERAL1
BACKWARD	    LITERAL1
FORWARD	        LITERAL1
RELEASE	        LITERAL1
MICROSTEP	    LITERAL1
INTERLEAVE	    LITERAL1
MICROSTEPPING	LITERAL1
```
