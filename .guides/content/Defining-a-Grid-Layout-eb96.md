You specify how many columns you want the grid layout to have using:
```
android:columnCount="number"
```
where number is the number of columns. 

You can also specify a maximum number of rows using:
```
android:rowCount="number"
```
but in practice you can usually let Android figure this out based on the number of views in the layout. Android will include as many rows as is necessary to display the views.


![](.guides/img/18grid.png)