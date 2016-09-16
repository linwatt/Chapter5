
![](.guides/img/38textview.png)
![](.guides/img/39.png)

### Used for:
displaying text (whoo hoo)

### Defining in XML
You define a text view in your layout using the 
**< TextView>** element. You use **android:text** to say what text you want it to display, usually by using a string resource:
![](.guides/img/37.png)

The TextView API includes many attributes to control the text view’s appearance, such as the text size. To change the text size, you use the android:textSize attribute like this:
```
android:textSize="14sp"
```
You specify the text size using **scale-independent pixels (sp)**. Scale-independent pixels take into account whether users want to use large fonts on their devices. A text size of 14sp will be physically larger on a device configured to use large fonts than on a device configured to use small fonts.

The definite guide is https://developer.android.com/reference/android/widget/TextView.html 

### Using it in your Activity Code
You can change the text displayed in your text view using code like this:
![](.guides/img/40.png)


