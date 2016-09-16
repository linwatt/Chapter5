We also need to tell it what row and column it should live in using **android:layout_row** and **android:layout_column**.

The row and column indices start from 0, so if you want a view to appear in the first column and first row, you use:
```
android:layout_row="0"
android:layout_column="0"
```

Apply this to our layout by putting the text view in column 0, and the editable text field in column 1:

![](.guides/img/26.png)
