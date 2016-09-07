You can also position views relative to other views. You do this when you want views to stay aligned in some way, irrespective of the screen size or orientation. 

In order to position a view relative to another view, the view you’re using as an anchor must be given an ID using the *android:id attribute*:
```
android:id="@+id/button_click_me”
```

Here’s how you create a layout with two buttons, with one button centered in the middle of the layout, and the second button positioned underneath the first:

![](.guides/img/16ids.png)

The lines **android:layout_alignLeft="@+id/button_click_me”** and  **android:layout_below="@+id/button_click_me”** ensure that the second button has its left edge aligned to the left edge of the first button, and is always positioned beneath it.
