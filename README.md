# BasicCAD

We are creating a caster.

---
## Table of Contents
* [Table of Contents](#Table-of-Contents)
* [Base](#Base)
* [Mount](#Mount)
* [Fork](#Fork)
* [Tire](#Tire)
* [Wheel](#Wheel)
* [AxleCollarBearings](#AxleCollarBearings)

## Base

### Description

The first assignment is to create the caster base.  The base's dimensions are 200 mm x 120 mm and 8 mm thick.  It has 6 holes 10 mm wide and 20 mm from the edge equally spaced along the edges.

### Evidence
[The Base in Onshape](https://cvilleschools.onshape.com/documents/0d70f655203ca304cb3c5b7d/w/f55603f962f6fc74f5548a68/e/41d730c570a8d75fce9f51b6)

### Image

<img src="https://github.com/OneCHSEngr/BasicCAD/blob/master/images/Base.jpg?raw=true" alt="The Base" width="200">

### Reflection

This was my first Onshape part and [following along with Dr. Shields made it super easy.](https://www.youtube.com/watch?v=93BFUD-HAG8&feature=emb_title&scrlybrkr=5670f0b4)  I learned about 
* sketching (shortcut **shift-s**)
* constructions lines (shortcut **Q**)
* dimensions (shortcut **D**)
* extruding both add and remove (shortcut key **E**)
* linear patterns (no shortcut)

Onshape is awesome.  I found it really helpful to rename all my sketches.  It is going to be a GREAT year in engineering.

---


## Mount

### Description

The second assignment is to make the mount. It is a square peice with 4 smaller holes near the 4 corners and a larger hole in the center.

### Evidence

[The Mount in Onshape](https://cad.onshape.com/documents/0f64acd659b6f144b8401d34/w/8ddf26f38822830b90c63ec8/e/58d05c1f88ff7eb902ea2dcc)

### Image



### Reflection

I very much enjoyed making this peice. It was simple and didn't require much knowlage. It was much like the previous peice, the base, because it had the 4 holes around the outside. I did do something different this time though, I didn't do the linear pattern after extruding the main part. Instead, I used a linear pattern in the sketch.

---


## Fork

### Description

A base circle with two reectangles extruded out of it and on the other side one cylinder extruded. Filleted edges.

### Evidence

[The Fork in Onshape](https://cad.onshape.com/documents/e2135307d73952fcf7ad0bdd/w/107b47cd6a7cb28dcafceef6/e/8f92bf454d3878bb6e0c97c8)

### Image

### Reflection

I learned how to fillet in this part.

---


## Tire

### Description

A symmetric trapezoid revolved in to a 3d shape.

### Evidence

[The Tire in Onshape](https://cad.onshape.com/documents/42cc059c0af575ec245c3ade/w/e07ac3e1d3171ce249043c0e/e/78eccdfa95e7abde0b3d4880)

### Image

### Reflection

I learned how to revolve a sketch into a solid circular 3d shape.

---


## Wheel

### Description

Similar to the tire, I started out with sketching one shape and then revolving it around into the wheel. The shape looked similar to an "I.' After revolving it, I cut holes into the side and added a bearing.

### Evidence

[The Wheel in Onshape](https://cad.onshape.com/documents/ce403b6333b464c5854d3454/w/20a942f6a05a0be872aa5dc2/e/4608a7c5cfb338e1da83d3ba)

### Image

### Reflection

I learned how to put two parts into one document. I also got more practice with revolving and remove extruding.

---


## AxleCollarBearings

### Description

I extruded a circle into a cylinder and then added a small rectangular divot into one of the ends. Then I made another part (the collar) and added that to the side with the divot. The collar also had a hole going through one side.

### Evidence

[The Axle/Collar/Bearings in Onshape](https://cad.onshape.com/documents/1b17bfcd9bbcebd8be2ae8d8/w/36eea3232a8a6b9b38aba88b/e/6474f39e006531d639bb57e7)

### Image

### Reflection

I got to work more on everything and practice.

---

## Dorthy's Dowel Pins

### Description

I made different widths and lengths of dowel pins using the chart stuff in Onshape.

### Evidence

[The Dorthy's Dowel Pins in Onshape](https://cvilleschools.onshape.com/documents/489abc522604910137bdac21/w/f02e7ecee5dd9fb1dc2737f0/e/4175451c12ee256d8cf99d1a)

### Reflection

I was very intrigued about learning more in Onshape. I thought that using the charts to make different combinations was a very smart way of shortening the time spent creating objects.

---

## Finite LED Blinker

### Description

I made a LED light up by fading using arduino code.

### Evidence

int led = 9;           
int brightness = 0;    
int fadeAmount = 5;    

void setup() {
  pinMode(led, OUTPUT);
}


void loop() {
  analogWrite(led, brightness);

  brightness = brightness + fadeAmount;

  if (brightness <= 0 || brightness >= 255) {
    fadeAmount = -fadeAmount;
  }
  delay(30);
}

### Reflection

I learned how to make values change incrementally.
