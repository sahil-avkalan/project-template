https://www.youtube.com/watch?v=nB8fQWFhtFs&list=PL6Fiih6ItYsXzUbBNz7-IvV7UJYHZzCdF&index=9
Blender: Transform Pivot Points, Bounding Box, Active Element & Proportional Editing  
1. Transform Pivot Point  
  
Previously, we learned how to create a mesh. To change the origin point, first select the desired vertex and then right-click and choose Set Origin. Under Set Origin, we get options such as Origin to 3D Cursor.  
  
When working in Edit Mode, the origin point of the mesh is visible. If there are multiple objects in the scene, the origin point is different for each object. In Edit Mode, however, we are working with the mesh geometry rather than separate objects.  
  
While working with multiple vertices or faces, we can use the Transform Pivot Point settings to control the point around which the selected geometry is transformed.  
  
The main pivot options include:  
  
Median Point – Transformation takes place around the center of the selected elements.  
3D Cursor – The selected geometry rotates or scales around the 3D Cursor.  
Bounding Box Center – The center of the bounding box is used as the pivot.  
Individual Origins – Each selected element uses its own origin for transformation.  
Active Element – The active selected element is used as the pivot.  
  
For example, if we select a vertex and press R, the selected geometry rotates around the currently active pivot point.  
  
2. Bounding Box Center  
  
The Bounding Box is an imaginary box that surrounds the selected geometry. Its center can be used as the transformation pivot.  
  
If we select a cube and use Bounding Box Center, the cube rotates around the center of its bounding box.  
  
If we select only a vertex and rotate it, the result is different because the bounding box is created according to the selected geometry.  
  
The bounding box changes according to the selected elements and provides a reference for transformation.  
  
3. 3D Cursor as Pivot  
  
If we select 3D Cursor as the Transform Pivot Point, the selected geometry rotates around the position of the 3D Cursor.  
  
To move the 3D Cursor, use:  
  
Shift + Right Click  
  
After placing the 3D Cursor, select the required geometry and press R to rotate it around the cursor.  
  
4. Individual Origins  
  
When Individual Origins is selected as the Transform Pivot Point, every selected element uses its own origin as the center of transformation.  
  
For example, if multiple objects are selected and we rotate them using Individual Origins, each object rotates around its own origin instead of rotating around a common center.  
  
This is useful when we want several objects to transform independently while applying the same transformation.  
  
5. Active Element  
  
The Active Element option uses the currently active element as the pivot point.  
  
First, select multiple elements and then select one element as the active element. The active element acts as the center of rotation or scaling.  
  
For example, if a cube is selected and one vertex is made active, that vertex can be used as the pivot for transformation.  
  
6. Transform Orientation and Pivot Point  
  
The Transform Orientation determines the direction in which transformation takes place, while the Transform Pivot Point determines the point around which the transformation occurs.  
  
When we press R, we can rotate the selected geometry. We can also constrain the rotation to a particular axis:  
  
R + X → Rotate around the X-axis  
R + Y → Rotate around the Y-axis  
R + Z → Rotate around the Z-axis  
  
Similarly, transformation can be performed using the X, Y, and Z directions.  
  
7. Snap with Active Element  
  
When the Active Element is selected as the pivot, we can use snapping to accurately position geometry.  
  
Enable Snapping and set the snap element to Vertex. With the snapping option set to Active, the selected geometry can be moved precisely relative to the active element.  
  
8. Add and Select Objects  
  
Press Shift + A to open the Add menu. From here, we can add different mesh objects such as a cube, sphere, cylinder, etc.  
  
In Edit Mode, press Space to search for commands. We can also select a vertex and press P to access the Separate options.  
  
9. Proportional Editing  
  
To enable Proportional Editing, press O.  
  
When Proportional Editing is enabled, transforming one vertex also affects nearby vertices within a certain radius. This allows us to create smooth and natural changes in the mesh.  
  
For example, if we select one vertex and move it, the surrounding vertices will also move gradually according to their distance from the selected vertex.  
  
This is useful for smoothly modifying the shape of a mesh instead of moving only one vertex.  
  
The influence area can be adjusted using the mouse wheel:  
  
Scroll up → Decrease the influence area.  
Scroll down → Increase the influence area.  
10. Randomize Transform  
  
Blender also provides a Randomize Transform option, which can be used to randomly modify the position, rotation, and scale of selected objects.  
  
To use it:  
  
Select the required object or objects.  
Open the Transform options.  
Choose Randomize Transform.  
Adjust the required settings.  
  
Randomization can be controlled using parameters such as:  
  
Random Seed  
Location  
Rotation  
Scale  
  
The Random Seed changes the random pattern. If we change the seed value, Blender generates a different random arrangement.  
  
This feature is useful when we want to create natural-looking variations among multiple objects instead of manually transforming each object.
![](attachments/Screenshot%202026-08-28%20at%209.46.13%20PM.png)![](attachments/Screenshot%202026-08-31%20at%206.54.20%20PM.png)![](attachments/Screenshot%202026-08-31%20at%206.58.33%20PM.png)![](attachments/Screenshot%202026-08-31%20at%206.59.08%20PM.png)![](attachments/Screenshot%202026-08-31%20at%206.59.58%20PM.png)![](attachments/Screenshot%202026-08-31%20at%207.05.40%20PM.png)![](attachments/Screenshot%202026-08-31%20at%207.06.32%20PM.png)![](attachments/Screenshot%202026-08-31%20at%2011.30.22%20PM.png)![](attachments/Screenshot%202026-08-31%20at%207.08.16%20PM.png)![](attachments/Screenshot%202026-08-31%20at%207.08.35%20PM.png)![](attachments/Screenshot%202026-08-31%20at%207.18.07%20PM.png)![](attachments/Screenshot%202026-08-31%20at%207.20.14%20PM.png)![](attachments/Screenshot%202026-08-31%20at%207.20.46%20PM.png)![](attachments/Screenshot%202026-08-31%20at%2011.30.35%20PM.png)![](attachments/Screenshot%202026-08-31%20at%207.24.37%20PM.png)![](attachments/Screenshot%202026-08-31%20at%207.36.46%20PM.png)![](attachments/Screenshot%202026-08-31%20at%207.59.41%20PM.png)![](attachments/Screenshot%202026-08-31%20at%208.02.01%20PM.png)![](attachments/Screenshot%202026-08-31%20at%208.02.54%20PM.png)![](attachments/Screenshot%202026-08-31%20at%2011.34.25%20PM.png)![](attachments/Screenshot%202026-08-31%20at%208.08.12%20PM.png)![](attachments/Screenshot%202026-08-31%20at%208.11.21%20PM.png)