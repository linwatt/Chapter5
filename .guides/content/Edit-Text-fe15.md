![](.guides/img/42edittext.png)
![](.guides/img/43.png)

### Used for:
Allows you to edit text

### Defining in XML
You define an editable text view in XML using the 
**< EditText>** element. You use the **android:hint** attribute to give a hint to the user as to how to fill it in.
![](.guides/img/41edit.png)
You can use the **android:inputType** attribute to define what type of data you’re expecting the user to enter so that Android can help them. 
As an example, if you’re expecting the user to enter numbers, you can use
```
android:inputType="number"
```
to provide them with a number keypad. 

### Using it in your Activity Code
You can retrieve the text entered in an editable text view like this:
![](.guides/img/44.png)