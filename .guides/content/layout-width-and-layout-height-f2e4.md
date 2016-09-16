**android:layout_width and android:layout_height are mandatory attributes for all views, no matter which layout you use.**

```
android:layout_width="wrap_content"
```
means that you want the view to be just wide enough for its content to fit inside it—for example, the text displayed on a button or in a text view. 

The code:
```
android:layout_width="match_parent"
```
means that you want the view to be as wide as the parent layout.

They can take the values wrap_content, match_parent, or a specific dimension value such as 16dp.
