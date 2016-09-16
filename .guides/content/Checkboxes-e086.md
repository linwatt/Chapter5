
![](.guides/img/59.png)
![](.guides/img/60.png)

### Used for:
Check boxes let you display multiple options to users. They can then select whichever options they want. Each of the checkboxes can be checked or unchecked independently of any others.


### Defining in XML
You define each checkbox in XML using the **< CheckBox>** element. You use the **android:text** attribute to display text for each option. 

![](.guides/img/58checkboxes.png)

### Using them in your Activity Code
Just like buttons, you can respond to the user clicking a checkbox by using the **android:onClick** attribute in the layout XML, and setting it to the name of the method you want to call in your activity code. 

You then define the method in your activity like this:
![](.guides/img/61.png)

You can find weather a particular checkbox is checked using the **isChecked() method**. It returns **true** if the checkbox is checked:
```
CheckBox checkbox = (CheckBox) findViewById(R.id.checkbox_milk);
boolean checked = checkbox.isChecked();
if (checked) {
  // do something
}
```