Journal 

This is my journal of the design and building process of 3D Vase.
You can view this journal in more detail on Hack Club Blueprint

Journal Write #1 ---- Establishing the complex geometry and foundational sketches ----  30 min
My goal for this design was to create a vase with a complex, fluid aesthetic using Loft Geometry, which is challenging because the profiles must be precisely aligned. I decided on a polygon shape with multiple sides for the cross section to achieve the "fluted" or flowy look without making the sides too sharp.

I spent some time drawing and dimensioning four separate polygon profiles using Offset Planes. I needed one for the base, one for the widest point (the "bulb"), one for the neck, and one for the rim.

The greatest challenge here was not just drawing the polygons, but ensuring their centers were perfectly aligned on the vertical axis and that their sizes were calculated. This involved constant dimensioning and checking to prevent loft errors later on. I used the Symmetry constraint extensively to save time and guarantee uniformity.

<img width="1580" height="1328" alt="image" src="https://github.com/user-attachments/assets/284b07e5-fa29-4d7b-a346-6ce58c879754" />

<img width="1594" height="1394" alt="image" src="https://github.com/user-attachments/assets/4ad1f1e6-9c22-4536-b379-1d44010c3e5c" />


Journal Write #2 ---- Executing the Loft and Debugging the Flow ----  1 hour

This hour was dedicated to applying the Loft command to connect the four established profiles. My initial attempt yielded a distorted shape because the software couldn't correctly map the 16 vertices across the planes.

I had to pause the loft process and spend about 30 minutes revisiting the sketches to ensure a consistent start point and direction for the geometry on every single profile. Once the point mapping was corrected, the loft executed cleanly, producing the basic body shape.

The remainder of the hour was spent refining the profile flow, adjusting the height of the middle planes, and confirming the smooth, hourglass curve (as shown in the grey image) that would serve as the canvas for the final twist.

<img width="1584" height="1408" alt="image" src="https://github.com/user-attachments/assets/b372938a-03fd-405e-ade1-9432b887d2b8" />


Journal Write #3 ---- Making Dynamic Geo (The Twisty Part) - making it aesthetic ---- 1 hour

With the basic structure complete, I moved on to the signature feature which was the spiral twist. I used the Twist/Deform modification tool to rotate the entire body.

I experimented with different rotation angles. A full 180 degree twist looked too aggressive and might lead to structural weakness in the ribs. I ultimately settled on a 120 degree rotation over the vertical axis, which creates a noticeable, dynamic flow without compromising the integrity of the fluted design. This required multiple iterations and renders to basically visually confirm the balance was correct.

I also finalized the upper rim structure, ensuring the top opening remained a clean polygon to give the design a clean finish.

<img width="1608" height="1368" alt="image" src="https://github.com/user-attachments/assets/ea9150d3-6d18-4007-bc37-6514f370966b" />

<img width="2398" height="1484" alt="image" src="https://github.com/user-attachments/assets/968175ee-31ca-43b5-bdcb-01f4a7c55d5c" />


Journal Write #4 ---- Finalizing Proportions and Aesthetic Color Choices ----

The final hour was dedicated to refining the proportions and making crucial aesthetic decisions.

I reviewed the existing geometry and felt the neck, or the end tip of the vase, was too short. To achieve a more elegant and balanced look, I performed a structural modification: I went back to my sketch planes and increased the height distance of the upper profile by 20mm. This results in a noticeably longer and more graceful neck. This small change was a critical step in finalizing the overall aesthetic appeal.

With the structure finalized, I began experimenting with materials and color rendering to visualize the final product, cuz lwk it looked like a boring vase if it wasn't given a bright color. I first applied a simple, solid red material. I intentionally experimented with rendering the model using alternating Red and Green vertical segments. This decision instantly created a vibrant, Christmas-themed design that maximizes the visual impact of the 120 degree twist and the intricate ribbing. I also felt like, since it was almost Christmas Season, why not give it this look with red and green colors.

<img width="2358" height="1502" alt="image" src="https://github.com/user-attachments/assets/43e4e888-8e48-480a-87a4-ab5d2ff51542" />

<img width="2374" height="1480" alt="image" src="https://github.com/user-attachments/assets/3fe9942d-ebe2-418e-816a-fc1fe6acb8a1" />



