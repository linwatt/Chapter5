An alternative approach is to specify the padding in a dimension resource file instead. Using a dimension resource file makes it easier to maintain the padding of all the layouts in your app.  You use a dimension resource file by setting the padding attributes in your layout file to the name of a dimension resource like this: 


![](.guides/img/7dimen.png)
![](.guides/img/8dimenRes.png)

Android then looks up the values of the attributes at runtime in the dimension resource file. This file is located in the app/src/main/res/values folder, and it’s usually called **dimens.xml**: 

Similar to the strings example we saw earlier, we put the actual value in the values folder instead of hard coding it in the AndroidManifest.xml