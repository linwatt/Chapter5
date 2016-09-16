You can add views to a grid layout in a similar way to how you add views to a linear layout:

![](.guides/img/20w3b.png)

Just like a linear layout, there’s no need to give your views IDs unless you’re explicitly going to refer to them in your activity code. The views don’t need to refer to each other within the layout, so they don’t need to have IDs for this purpose.
By default, the grid layout positions your views in the order in which they appear in the XML. So if you have a grid layout with two columns, the grid layout will put the first view in the first position, the second view in the second position, and so on.
if you remove one of your views from the layout, it can drastically change the appearance of the layout.


![](.guides/img/19app.png)