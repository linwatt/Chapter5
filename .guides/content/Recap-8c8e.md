- GUI components are all types of view. They are all subclasses of the android.view.Viewclass.

- All layouts are subclasses of the android.view.ViewGroup class. A view group is a type of view that can contain multiple views.

- The layout XML file gets converted to a ViewGroup containing a hierarchical tree of views.

- A relative layout displays child views relative to other views, or relative to the parent layout.

- A linear layout lists views either horizontally or vertically. You specify the direction using the **android:orientation** attribute.

- A grid layout divides the screen into a grid of cells so that you can specify which cell (or cells) each view should occupy. 
  - Use **android:columnCount** to say how many columns there should be. 
  - Use **android:layout_row** and **android:layout_column** to say which cell you want each view to appear in. 
  - Use **android:layout_columnSpan** to say how many columns the view should spread across.

- Use **android:padding** attributes to specify how much padding you want there to be around a view.

- Use **android:layout_weight** in a linear layout if you want a view to use up extra space in the layout.

- **android:layout_gravity** lets you say where you want views to appear in their available space.

- **android:gravity** lets you say where you want the contents to appear inside the view.

### GUI Components
- <**ToggleButton**> defines a toggle button which allows you to choose between two states by clicking a button.

- <**Switch**> defines a switch control that behaves in the same way as a toggle button. It requires API level 14 or above.

- <**CheckBox**> defines a checkbox.

- To define a group of radio buttons, first use <**RadioGroup**> to define the radio group. Then put individual radio buttons in the radio group using <**RadioButton**>.

- Use <**ImageView**> to display an image.

- <**ImageButton**> defines a button with no text, just an image.

- Add scrollbars using <**ScrollView**> or <**HorizontalScrollView**>.

- A **Toast** is a pop-up message.

