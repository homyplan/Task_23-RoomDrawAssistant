# Task_23-RoomDrawAssistant

Help floor plan drawing process with room draw feature.

Add buttons for a few new ReactPlanner elements - rooms with different shape (consisting of walls and automatic floor/area).

Use images included in the repo for icons/thumbnails

Follow the react-planer's structure of the objects in catalog.

Prepare separate object for each component

![catalog](https://user-images.githubusercontent.com/38282085/145831467-543a98bf-4b47-41a9-9a45-7997a9cc3e33.JPG)

UX:

1. Select from objects catalog

![rooms](rooms.JPG)

3. Glue to the cursor during dragging (for precise operation)
4. Insert a room like normal element (use provided images for button images)
4. Allow for Translate, Scale, Rotate in second step (after insert). Lack of Rotate controller on images below but it should be there.

![rooms](RoomAssistant_01.JPG)
![rooms](RoomAssistant_02.JPG)
![rooms](RoomAssistant_03.JPG)
![rooms](RoomAssistant_04.JPG)


5. Take into consideration removal of double vertices, and double lines (don't brake existing functionality). Make it weorking with existing colapse vertices feature.

Additinal feartures:

- transform controllers after insert (translate, rotate, scale), like for the element
- snapping to existing wall vertex
- show popup window on the begining of creation process for user input (width,depth,rotatin,mirror). UI according to picture below:

![Room creator](Room_creator.JPG)

