# Week 8

## [Home](https://dtxiong.github.io/rapid-prototyping/)

On Monday, I worked with Pablo from the systems team. He helped provide dimensions for how large the primary/secondary mirror should be. We are now leaning towards trying to create a fiberglass layup composite of the mylar parabolic mirror, like this video: [https://www.youtube.com/watch?v=8CLRTa_ocmo]. 

This is done by first getting a flat surface. We could use a PVC plate, which is smooth. Then, we adhere a sheet of thin mylar to a circle on the PVC plate. We introduce pressure on the bottom so that slowly the mylar will rise to form a parabolic shape. We can keep the parabolic shape by using a fiberglass layup. This will have to be done in an open and clean space. (Pablo has experience doing it in his garage). After the fiberglass hardens we can cut out the mylar sheet, and then reinforce the sides with a wooden or 3D printed circle. Finally, we would cut the hole in the center for the rays to pass through. 

Actually, this mylar sheet will be a catenoid, not a parabola (least surface for given volume). However, it will be close enough (taylor approx of cosh is similar to parabola) for our needs. In the video, the focal point was able to light a piece of firewood. 

The dimensions calculated by the sytem integration team are: 2.5 ft Primary mirror diameter, 5.4 in. inner diameter (hole). By having the height of the parabola be 3 inches, we would get a focal length of 18.75 inches. 

One idea from the systems team was to have a flat mirror at the halfway height to the focus. This would direct the rays back towards the vertex, but the secondary mirror would be very large and be half the radius of the primary mirror. This will lose 25% power from the rays. 

The alternative method (explained in last week's documentation) was to create a parabolic mirror with the same focus point. This way, the secondary mirror would have a diameter of 5.4 in, which is the same as the diameter of the hole. The secondary mirror would be proportional to the primary mirror, so it would have a height of ~1 inch. 

Another idea I looked at was the possibility of having a one-way secondary mirror. This would allow light to still pass through the secondary mirror directly into the hole, but still be able to reflect light from other parts of the primary mirror. The calculations are shown here: 

![One-Way-Calculations](./File_000 (6).png)

Because the area of the primary mirror is larger than twice the area of the secondary mirror, we will use 100% reflection. 

On Wednesday, we had the midterm review. 
