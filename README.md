# holographic-view
#create a awsome box
mybox= new box
color:color.yellow
length: 15
#enable fog on the scene and set its color
Hologram.scene.fog=
color: "#FFFC00"
near: 1
far:10
#add a film effect
Hologram.effects.file = yes
mybox.animate
rotationX : 180
time : 2
repeat: infinity
#animate the car
Car.animate
rotation: "0 360 0"
time: 10
repeat: Infinity
