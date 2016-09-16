![](.guides/img/63.png)
![](.guides/img/64.png)

### Used for:
Lets you display multiple options to the user, but the user is restricted to only one selection.

### Defining in XML
You start by defining a radio group, a special type of view group, using the **< RadioGroup>** tag. Within this, you then define individual radio buttons using the **< RadioButton>** tag:

![](.guides/img/62radio.png)


The radio group containing the radio buttons is a subclass of LinearLayout. You can use the same attributes with a radio group as you can with a linear layout.
For example you can choose to display the radio buttons in a horizontal or vertical list

### Using them in your Activity Code
You can find which radio button is selected using the **getCheckedRadioButtonId()** method:
```
RadioGroup radioGroup = findViewById(R.id.radioGroup);
int id = radioGroup.getCheckedRadioButtonId();
if (id == -1){
  //no item selected
}
else{
  RadioButton radioButton = findViewById(id);
}
```


You can respond to the user clicking a radio button by using the android:onClick attribute in the layout XML, and setting it to the name of the method you want to call in your activity code.

You then define the method in your activity like this:
```
public void onRadioButtonClicked(View view){
  RadioGroup radioGroup = findViewById(R.id.radioGroup);
  int id = radioGroup.getCheckedRadioButtonId();
  switch(id){
    case R.id.radio_cavemen:
      // Cavemen win
      break;
    case R.id.radio_astronauts:
      // astronauts win
      break;
  }
}

