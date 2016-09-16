![](.guides/img/65spinner.png)
![](.guides/img/66.png)

### Used for:
Gives you a drop-down list of values from which only one can be selected.

### Defining in XML
You define a spinner in XML using the **< Spinner>** element. You add a static array of entries to the spinner by using the **android:entries** attribute and setting it to an array of strings.
![](.guides/img/67.png)
You can add an array of strings to strings.xml like this:
![](.guides/img/68.png)

### Using it in your Activity Code
You can get the value of the currently selected item by using the **getSelectedItem()** method and converting it to a String:

![](.guides/img/69.png)