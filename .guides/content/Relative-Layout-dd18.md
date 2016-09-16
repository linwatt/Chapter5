As you already know, a relative layout allows you to position views relative to the parent layout, or relative to other views in the layout.

![](.guides/img/5relative.png)



The *xmlns:android* attribute is used to specify the Android namespace, and you must always set it to "http://schemas. android.com/apk/res/android". 

The *android:layout_width* and *android:layout_height* attributes specify how wide and high you want the layout to be. 

You can set android:layout_width and android:layout_height to "match_parent", "wrap_content" or a specific size such as 10dp - 10 density-independent pixels.

"wrap_content" means that you want the layout to be just big enough to hold all of the views inside it, and "match_parent" means that you want the layout to be as big as its parent—in this case, as big as the device screen minus any padding. 

You will usually set the layout width and height to "match_parent".
