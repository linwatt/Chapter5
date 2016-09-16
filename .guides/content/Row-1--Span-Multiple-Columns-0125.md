The second row of the grid layout is composed of an editable text field that starts in the first column and spans across the second. The view takes up all the available space.

![](.guides/img/27.png)

To get a view to span multiple columns, you start by specifying which row and column you want the view to start in. We want the view to start in the first column of the second row, so we need to use:
```
android:layout_row="1"
android:layout_column="0"
```

We want our view to go across two columns, and we can do this using the **android:layout_columnSpan** attribute like this:
```
android:layout_columnSpan="number"
```
Where 'number' is the number of columns we want the view to span across. In our case, this is:
```
android:layout_columnSpan="2"
```

All together, here's the code for the message view:

![](.guides/img/28code.png)