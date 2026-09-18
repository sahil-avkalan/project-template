https://www.youtube.com/watch?v=lf6jUWeCKMg&list=PLlHtucAD9KT19ckHqXpPSStZOyDSq9AW-&index=5
Variables, we can store multiple properties and reuse them throughout our design. On the right-hand side, below Page Settings, we can find Local Variables. When we click Open Variables, a menu appears.  
  
If we click Create Variable, we get four options:  
  
Color  
Number  
String  
Boolean  
  
For example, if we select Color, we can name the variable Gray and use the Eyedropper to select its value.  
  
If we are working with Primitives, we can also create a new library/collection for our Surface values. To do this, click the three dots, select Create Collection, and give it a name such as UI Palette.  
  
Then, by right-clicking the Value field and going to Primitives, we can view our collections and select the required Surface value. This helps us keep our design values organized and reduces the chances of making mistakes when applying colors or surfaces.
Number Variable  
1) Click on Local Variables, then go to New Collection and select Component Data.  
2) Click on Create Variable and select the Number variable type.  
3) In Auto Layout, we can use the variable for the required text/value and then duplicate it as needed.  
4) After duplicating it, go to the Auto Layout settings. On the right-hand side, the Dimension option is available.  
5)We can click on the required value/field and enter the number value there.  
  
In simple words: Number Variables in Figma are used to store numerical values so that the same value can be reused and easily changed across different designs.
String  
1)If we want to give the same text a name using multiple variables, we can use a String.  
2)With String, we can select just one variable and add the text in the Value field using Continue.  
3)By continuing this process, we can change the text for multiple variables.  
4)In comparison, with a Component Property, we can make the text change for only one variable at a time.
Boolean Variable  
1) To create a Boolean variable, click Create Variable and select Boolean under Local Variables. Give the variable a name, such as Switch.  
2) In the Canvas, select the feature or layer you want to control.  
3)On the right-hand side, go to the Layers section and use the eye/visibility option to select and apply the Boolean variable.  
3) The Boolean variable is used to control visibility and to trigger special actions in Prototype mode.  
4) It is mainly useful for turning elements ON or OFF based on the Boolean value (True / False).
   Styles vs. Variables — Difference  
Styles  
1)  In Styles, we have typeface, shadows, and colors.  
5) If we go to Fill, click the + icon, and select Style, we can create a style.  
3)By going to the Properties section and clicking +, we can add multiple layers to the style.  
4)In Styles, we can create layering/combinations of properties.  
Variables  
1)In Variables, we need a concrete and specific individual value.  
2)We can store values such as integers inside a variable.  
6) Styles do not support aliases in the same way, and we cannot create multiple value variations within a single style.  
7) With Variables, we can create multiple variations/values.  
8) Variables also support scoping.  
9) Variables can be used for text and strokes.  
Example: Creating and Using a View Count Variable  
step1)Go to Local Variables.  
step2) Click Create collection.  
step3) Click Create variable and select Number.  
step4) Give the variable the name view-count.  
step5) Set its value to 999.  
step6) On the canvas, select the view layer.  
step7) On the right-hand side, in the Text section, click the diamond icon.  
step8) Select the view-count variable.  
step9) Turn on Prototype mode.  
step10) Under Interactions, click None.  
step11) Select Set variables.  
step12) Choose view-count.  
step13) In the To field, enter view-count + 1.  
step14) Press Enter.![](attachments/Screenshot%202026-09-18%20at%2011.02.11%20AM.png)
![](attachments/Screenshot%202026-09-18%20at%2010.58.21%20AM.png)![](attachments/Screenshot%202026-09-18%20at%2010.57.40%20AM.png)![](attachments/Screenshot%202026-09-18%20at%2010.57.34%20AM.png)