![](.guides/img/56.png)
![](.guides/img/57.png)

### Used for:
A slider control that acts in the same way as a toggle button. If you want to use a switch in your app, make sure it uses a minimum SDK of API level 14.

### Defining in XML
You define a toggle button in XML using the **< Switch>** element. You use the **android:textOn** and **android:textOff** attributes to say what text you want the switch to display depending on the state of the switch:

![](.guides/img/54.png)

### Using it in your Activity Code
You get the switch to respond to the user clicking it by using the **android:onClick** attribute in the layout XML, and setting it to the name of the method you want to call in your activity code:
```
android:onClick="onSwitchClicked"
```

You then define the method in your activity like this:

![](.guides/img/55.png)