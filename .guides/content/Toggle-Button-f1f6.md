![](.guides/img/49toggle.png)
![](.guides/img/50.png)

### Used for:
A toggle button allows you to choose between two states by clicking a button.

### Defining in XML
You define a toggle button in XML using the 
**< ToggleButton>** element. You use the **android:textOn** and **android:textOff** attributes to say what text you want the button to display depending on the state of the button:
![](.guides/img/51.png)

### Using it in your Activity Code
You get the toggle button to respond to the user clicking it by using the **android:onClick** attribute in the layout XML. You give it the name of the method you want to call in your activity code:
![](.guides/img/52.png)

You then define the method in your activity like this:

![](.guides/img/53.png)