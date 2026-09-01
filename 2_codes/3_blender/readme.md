https://www.youtube.com/watch?v=YK0LIlPUE0U&list=PL6Fiih6ItYsXzUbBNz7-IvV7UJYHZzCdF&index=13
Part-13
This topic is divided into two parts: **2D and 3D**, because a 3D model is made up of multiple 2D faces.

Before starting, we first set up our scene. Go to **Overlays** and enable **Statistics** so that the required statistics are visible. Then go to **File → Defaults → Save Startup File** to save these settings as the default startup configuration.

To add-ons, go to **Edit → Preferences**. Now we can start working in 2D. Press **A** to select everything, then press **X** to delete the selected objects.

Next, select a vertex and press **E** to extrude it. If we press **1**, the corresponding axis/view is automatically selected. If we press **Y** and then **Enter**, the selected vertex will move or extrude in the **Y direction**. By selecting vertices and extruding them, we can create edges, boxes, cubes, and other shapes.

To create a face between two vertices, select the required vertices and press **F**. This creates a face. If we press **X** and choose **Only Faces**, the face is deleted while the vertices and edges remain.

Now press **A** to select everything and duplicate it. After moving the duplicate slightly, go to **Object Mode** and select one of the objects. Both objects may become selected because they are part of the same selection. We can also join objects using **Ctrl + J**.

Press **Tab** to return to **Edit Mode**. For **CAD Transform**, press **Alt + C**. Depending on the shortcut configuration, pressing **G** allows us to transform or move the selected vertices. We can place the selected vertex over another vertex.

To make vertices visible through the mesh, enable **X-Ray** by pressing **Alt + Z**. Now, when we create a selection box, we can select vertices that are positioned behind the visible geometry as well.

If we select all the geometry, we can see four vertices and two edges that are overlapping each other. To combine these overlapping vertices, right-click and select **Merge Vertices**. The shortcut is **M**, followed by **By Distance**.

After merging, we can see that two duplicate vertices have been removed. We can open the **Merge by Distance** dialog box to check the distance within which the vertices were merged. The same operation can be performed on the other side as well.

From the menu, go to **Tools → Auto Merge** to enable automatic merging. With **CAD Transform (Alt + C)** enabled, pressing **G** and then performing the transformation can automatically merge the vertices when they are brought together.

If we select an edge and press **E**, it performs an extrusion operation. This works similarly to creating a duplicate of the selected edge. By selecting an edge and extruding it, we can create another connected section and form shapes such as a cube.

### Advanced 2D Operations

For some advanced 2D operations, select an edge and rotate it slightly. Then, using the **TinyCAD** add-on, right-click and go to **TinyCAD → VTX AUTO**. This operation creates an additional vertex at the intersection of the selected elements.

If we select three vertices, we can use TinyCAD to create a circle passing through or connecting the selected points. In **TinyCAD**, select **CCEN – Circle Center** to create a circle.

We can also use **CCEN – Circle Center from Selected** to increase or adjust the number of vertices used to define the circle.

Finally, pressing **X** and selecting **Dissolve Vertices** removes the selected vertices while keeping the surrounding edges connected. Similarly, edges can be dissolved, and the way edges are dissolved is related to the surrounding faces.
![](attachments/Screenshot%202026-09-01%20at%203.55.09%20PM.png)![](attachments/Screenshot%202026-09-01%20at%203.59.07%20PM.png)![](attachments/Screenshot%202026-09-01%20at%204.01.44%20PM.png)![](attachments/Screenshot%202026-09-01%20at%204.04.17%20PM.png)![](attachments/Screenshot%202026-09-01%20at%204.31.12%20PM.png)![](attachments/Screenshot%202026-09-01%20at%204.32.13%20PM.png)![](attachments/Screenshot%202026-09-01%20at%205.05.09%20PM.png)![](attachments/Screenshot%202026-09-01%20at%205.13.40%20PM.png)![](attachments/Screenshot%202026-09-01%20at%205.18.56%20PM.png)![](attachments/Screenshot%202026-09-01%20at%205.33.27%20PM.png)