![](.guides/img/46.png)
![](.guides/img/47.png)

### Used for:
Usually used to make your app do something when the button’s clicked.

### Defining in XML
You define a button in XML using the **< Button>** element. You use the **android:text** attribute to say what text you want the button to display:
![](.guides/img/45button.png)

### Using it in your Activity Code
You get the button to respond to the user clicking it by using the **android:onClick** attribute in the layout XML, and setting it to the name of the method you want to call in your activity
```
android:onClick="onButtonClicked"
```

You then define the method in your activity like this:
![](.guides/img/48.png)