When you define a linear layout, you add views to the layout in the order in which you want them to appear. So if you want a text view to appear above a button, you must define the text view first: 

![](.guides/img/3.png)

With a linear layout, you only need to give your views IDs if you’re explicitly going to refer to them in your activity code. This is because the linear layout figures out where each view should be positioned based on the order in which they appear in the XML. Views don’t need to refer to other views in order to specify where they should be positioned.
