The layout you define using XML gives you a *hierarchical tree of views and view groups.* As an example, here’s a relative layout containing a button and an editable text field. The relative layout is a view group, and the button and text field are both views. The view group is the view’s parent, and the views are the view group’s children:

![](.guides/img/35.png)

Behind the scenes, when you build your app, the layout XML is converted to a ViewGroup object containing a tree of Views. In the example above, the button gets translated to a Button object, and the text view gets translated to a TextView object. Button and TextView are both subclasses of View. This is the reason why you can manipulate the views in your layout using Java code. Behind the scenes, all of the views are rendered to Java View objects.

![](.guides/img/36.png)