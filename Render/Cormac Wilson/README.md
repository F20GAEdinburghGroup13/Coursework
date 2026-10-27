# F20GA - Cormac Wilson

For my object I have decided to re-create my 710ml Stanley IceFlow™ Fast Flow Bottle in red and black. Please see an image below.
![IceFlow Fast Flow Bottle | 0.71L | Stanley 1913 GB](Images\waterbottlestanley.png "IceFlow Fast Flow Bottle | 0.71L | Stanley 1913 GB")

My Blender model will be a re-creation of this water bottle.

## Diary

- 15/10/2026 ->
  - Created initial water bottle body within the lid, I did this by creating a new cylinder mesh in object mode, I then changed into edit mode and deleted the top face of the bottle body, after this I added a rounded bevel (with ten segments) to the bottom of the main bottle body, this was to give it a nice and smooth base.
  - Created red material for the bottle body, the colour hex for the material colour I chose was to try and closely resemble the colours used for Stanley products, currently I have set the metallic property very high and the roughness quite low. I hope to make it more reminiscent of my actual water bottle later down the line.
- 16/10/2026 ->
  - Created initial lid part of the water bottle, I did this by creating a new cylinder mesh in object mode, I then changed into edit mode and used the transform tool to reduce its height and make it shorter, after this, I deleted its bottom face and positioned it over the empty water bottle lid top. I then added a small bevel with five segments to both top edge of the bottle body and the bottom edge of the bottle lid.
  - Created black material for the bottle lid, this is a black matt plastic, currently I have the roughness set pretty high to try and give it a matt looking effect with the metallic set to zero. It looks pretty good but later down the line I need to check it matches up with the actual water bottle lid.
- 17/10/2026 ->
  - Created the spout for the water bottle lid, I did this by using the inset faces tool to make a smaller face within the big face. After this I used the loop cut tool to make smaller loops within the new smaller face. I then used the extrude region tool to actually make the spout, after competing this I used the transform tool to individually mould each of the loop cuts to make the smooth curve between the lid face and the spout.
  - Added a bevel (with ten segments) to the top of the spout, this is too make it smooth and curved instead of it being a straight and sharp edge.
- 19/10/2026 ->
  - Added side screws base to water bottle lid, I created another new cylinder mesh in object mode and rotated it 90° degrees to the side I then positioned the screw centrally and moved it down and in so that it was in the side of the water bottle lid. I then applied the mirror modifier to it so that it would appear on the other side of the water bottle as well.
  - Added side screws to the water bottle lid, I created the actual screws that go into the side screws base on either side of the water bottle that I made earlier. I have also added a bevel to the outside edge of the screw to give it that angled side which makes it look like a screw. After this I added smaller face using the inset faces tool, I then used the transform tool to make a hole in the middle of the side screw, using the bevel tool (with ten segments) again on the edge of the hole to give it a nice smooth angle.
- 21/10/2026 ->
  - Created the initial handle component which connects from the side screws and their bases to the actual handle for the water bottle. I did this by creating a new cylinder mesh in object mode and rotated it 90° degrees to the side, I then used the transform tool to reduce its size and thickness. I then moved it in place between the side screw base and the side screw itself. After this, I used the bevel tool again to smooth the side faces to ensure that it was a smooth circle.
- 23/10/2026 ->
  - Have created initial handle parts from the side screws, I did this by selecting some of the faces which go around the outside of the handle base I made which is between the side screw and the side screw base, I then used the extrude tool to bring it forward. Whilst doing this, I also reduce the side of the handle base slightly, I simply made it not as thick and slightly thinner.
  - Used the scale tool locked along the Z axis to make the top of the handles flat instead of curved like they were previously.
  - Have added smooth by angle modifier to the handle and have also marked two of the edges of the side screw as sharp so when I shade as smooth, they stay sharp.
  - Have fixed geometry issues I was experiencing with the handle connectors, I was getting weird issues with lighting, there was duplicate vertices, I have removed it and fixed this issue.
- 24/10/2026 ->
  - Have recreated the handle. Did this by deleting the initial handle and then recreating it. I first made the cylinder that the handle is based off of before then extruding its top faces up to make the initial handle spine, before then using the scale tool on its top faces to flatten it out, into a straight line. After this I then continued up using the extrude tool to make the spine slightly thicker (for the black plastic bit) I then angled it and connected it together at the top. I enabled clipping for the mirror tool for this.
  - Added curves to the edges of the new handle spine and the edges of the side screws and the handle spine cylinder base. I did this by using the bevel tool.
  - Added materials to the handle spine, I did this by simply selecting the correct faces on the mesh, and selecting the correct material for them using the materials pane in the properties workspace on my Blender.
  - Added further curved edges to the handle spine, used the bevel tool to make the edges around the specific angle change section more curved compared to the straight lines I have previously.
- 27/10/2026 ->
  - Used the scale tool to slightly increase the width of the top part of the handle, along the x axis. Added new screenshot as well.
  - Created the bottle cap for the lid. I did this by using the edge select tool and selecting the top edge of the lid, I then duplicated it and cloned it into its own mesh object. I then filled it to give it a body and also used the extrude and the scale tool to make it taller in height and to make it slightly smaller so that it fits better within the lid.
  - Finished bottle cap for the lid. I edited the cylinder I made for it some more bu using the scale tool to get the correct size before then using the inset faces tool to make a smaller face for the gap where the lid walls go, I then usd the inset faces tool again to make the plug that goes into the bottle, next. After then, I them combined the faces for the plug in the middle, and the face of the actual cap together, this then created a flat surface for the top. Finally, I added some nice bevels to the plugs and also the angles on the outside along the top of the water bottle cap.
  - Added screenshots for all of the work that I have completed today.

## References

- IceFlow Fast Flow Bottle | 0.71L | Stanley 1913 GB (no date) [Stanley]. Available at: https://share.google/ZjCh81oiLelQbijs3 (Accessed: 22 October 2026).
