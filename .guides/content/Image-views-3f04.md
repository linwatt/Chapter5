![](.guides/img/70image.png)
![](.guides/img/73.png)

### Used for
Displaying an image

### Defining in XML
You first need to add an image file to your project as a **drawable resource**. If you expand the *app/src/main/res* folder in your project, you should see that there’s a folder called drawable. This is the default location for image resources. 

To add an image file to this folder, you simply drag the image file to it. If you want, you can use different image files depending on the screen density of the device. This means you can display higher-resolution images on higher-density screens, and lower-resolution images on lower-density screens. To do this, you create different drawable folders in *app/src/main/res* for the different screen densities. The name of the folder relates to the screen density of the device.

You then put different resolution images in each of the drawable folder, making sure that each of the image files have the same name. Android decides which image to use at runtime, depending on the screen density of the device it's running on. 

You define an image view in XML using the **< ImageView>** element. You use the **android:src** attribute to specify what image you want to display. You use the **android:contentDescription** attribute to add a string description of the image so that your app is more accessible:

![](.guides/img/71.png)

The **android:src** attribute takes a value of the form **"@drawable/ image_name"**, where image_name is the name of the image (without its extension). Image resources are prefixed with @drawable. @drawable tells Android that it’s an image resource located in one or more of the drawable folders.


### Using it in your Activity Code
You can set the image source and description in your activity code using the **setImageResource()** and **setContentDescription()** methods:

![](.guides/img/72.png)

This code looks for the image resource called starbuzz_logo in the drawable* folders, and sets it as the source of an image view with an ID of photo. When you need to refer to an image resource in your activity code, you use **R.drawable.image_name** where image_name is the name of the image (without its extension)
