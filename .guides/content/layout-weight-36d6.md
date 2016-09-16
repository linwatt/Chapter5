All of these views take up just as much vertical space in the layout as they need for their contents. So how do we make the Message text field taller? What we actually want is to make the Message text field stretch to take up any vertical space in the layout that’s not being used by the other views.

![](.guides/img/6.png)


In order to do this, we need to allocate some weight to the Message text field.

Allocating weight to a view is a way of telling it to stretch to take up extra space in the layout.
You assign weight to a view using
```
android:layout_weight="number"
```
where number is some number greater than 0.
