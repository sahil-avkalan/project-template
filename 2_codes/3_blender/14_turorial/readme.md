https://www.youtube.com/watch?v=b6lf31U40cE&list=PL6Fiih6ItYsXzUbBNz7-IvV7UJYHZzCdF&index=14
## Part 14 – Bevels, Chamfers, Offsets, and Precision Modeling

In this part, we will learn about **bevels and chamfers**, which are very useful in precision modeling. We use them frequently in precision modeling, although Blender does not make them as easy or parametric as some other CAD software.

To create a bevel, we use the shortcut **Ctrl + B**. When we press **B**, it affects the vertices without considering the actual face. Blender does not always recognize which edge is the original edge. As we drag the mouse, we can create a **chamfer**. To convert this into a proper bevel, we can use the **scroll wheel** to increase the number of segments.

We can also enter numerical values for the bevel. In the bottom-left corner, we have a **dialogue box** where we can adjust parameters such as the **Width** and **Segments**.

### Reconstructing a Destructive Operation

To reconstruct a destructive operation, go to **Active Element** and select everything. Then, make one of the selected elements the **Active Element**. From there, we can scale the geometry in any direction using **X, Y, or Z**.

As the value approaches zero, the selected geometry becomes increasingly stretched toward that direction. If we enter **0** and press **Enter**, the selected elements will be scaled to zero along that axis.

Next, we select the extra vertices that are not required. Press **X** and choose **Dissolve Vertices**. This removes the unnecessary vertices while keeping the required geometry intact.

### Using Offsets in Precision Modeling

Offsets are also very useful for precision modeling. Select the mesh and go to **Add-ons**. We can use the edge offset tool and set the required **Offset Amount**. The offset can be adjusted in any direction according to our requirements.

To select a face, we can press **F**. To move the **3D Cursor** to the center of the selected geometry, press **Shift + S** and choose **Cursor to Selected**.

### Creating and Splitting Faces

To create a face inside a hole, select one vertex and press **F** to create a connection. Then select all the required vertices and edges and press **F** again to create the face.

To remove unnecessary edges, open the **N panel**, go to **Tool**, and enable **Auto Merge**. Also enable the **Split Edges & Faces** option.

Now, select a vertex and extrude it outward. After moving it, left-click to confirm the operation. This divides the face, giving us two separate faces.

We can then extrude the geometry outward in 3D space. We can also use the **CAD Transform** add-on for more precise transformations.

For example, press **Alt + C**, then **G**, followed by **Space**. Select the required vertex, press **V**, and then press **Space**. Next, press **Shift + E** and choose **Edge Center**. This will automatically split the face.

However, when using **CAD Transform**, the face may not split in the same way. With Blender's default movement system, the face can be split. This method can accurately split a single face into multiple faces.

### Cleaning Up the Geometry

After creating the required geometry, select all unnecessary faces and edges and delete them.

Press **A** to select the edges, then press **Alt + F**, followed by **X**, and choose **Limited Dissolve**. This removes unnecessary edges while preserving the overall shape.

To create a large chamfer on a vertex, select the vertex and use **Ctrl + B + V**. Drag the mouse to adjust the size of the chamfer and then release it.

### Simplifying Difficult Geometry

The easiest way to clean up complicated geometry is to remove the parts that are making the modeling difficult. We can delete the faces surrounding the problematic area.

Press **X** and choose **Only Faces**. Once the unnecessary faces are removed, the remaining geometry becomes much easier to work with.

Finally, select the edges that are not required. Right-click, press **X**, and choose **Edges**. This removes the unwanted edges and leaves us with cleaner and more manageable geometry.