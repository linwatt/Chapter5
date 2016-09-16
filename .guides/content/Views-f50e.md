A **View** object occupies rectangular space on the screen. It includes the functionality all views need in order to lead a happy life in Androidville. Here are some of the most important:

<h2>Getting and Setting Properties</h2>
Each view is a Java object behind the scenes, and that means you can get and set its properties in your activity code. As an example, you can retrieve the value selected in a spinner or change the text in a text view. The exact properties and methods you can access depend on the type of view.

![](.guides/img/34.png)

<h2>Size and Position</h2>
You can specify the width and height of views so that Android knows how big they need to be. You can also say whether any padding is needed around the view.
Once your view has been displayed, you can retrieve the position of the view, and its actual size on the screen.

<h2>Focus Handling</h2>
Android handles how the focus moves depending on what the user does. This includes responding to any views that are hidden, removed, or made visible.

<h2>Event Handling and Listeners</h2>
Each of your views can respond to events. You can also create listeners so that you can react to things happening in the view. As an example, all views can react to getting or losing the focus, and a button (and all of its subclasses) can react to being clicked.


As a view group is also a type of view, this means that all layouts and GUI components share this common functionality.
