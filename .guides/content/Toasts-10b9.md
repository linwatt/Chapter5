![](.guides/img/83.png)
![](.guides/img/84.png)

### Used for
A toast is a simple pop-up message you can display on the screen.
Toasts are purely informative, as the user can’t interact with them. While a toast is displayed, the activity stays visible and interactive. The toast automatically disappears when it times out

### Using it in your Activity Code
You create a toast using activity code only. 

You can’t define one in your layout. To create a toast, you call the **Toast.makeText()** method, and pass it **three** parameters: a **Context** (usually this for the current activity), a **CharSequence** that’s the message you want to display, and an **int duration**. Once you’ve created the toast, you call its **show()** method to display it.Here’s the code you would use to create a toast that appears on screen for a short duration:
![](.guides/img/85.png)