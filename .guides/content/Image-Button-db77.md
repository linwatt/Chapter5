![](.guides/img/78.png)
![](.guides/img/79.png)

### Used for
An image button is just like a button, except it contains an image and no text

### Defining in XML
You define an image button in XML using the **< ImageButton>** element. You use the **android:src** attribute to say what image you want the image button to display:
![](.guides/img/76imageButton.png)

### Using it in your Activity Code
You get the image button to respond to the user clicking it by using the **android:onClick** attribute in the layout XML, and setting it to the name of the method you want to call in your activity code:
```
android:onClick="onButtonClicked”
```

You then define the method in your activity like this:

![](.guides/img/77.png)