You then put different resolution images in each of the drawable* folders, making sure that each of the image files has the same name. Android decides which image to use at runtime, depending on the screen density of the device it’s running on. As an example, if the device has an extra high density screen, it will use the image located in the drawable-xhdpi folder. If an image is added to just one of the folders, Android will use the same image file for all devices. It’s common to use the drawable folder for this purpose.


<table style="width:100%">
  <tr>
    <th>Folder</th>
    <th>Device Type</th> 
  </tr>
  <tr>
    <td>android-ldpi</td>
    <td>Low density screens, around 120 dpi
</td> 
  </tr>
  <tr>
    <td>android-mdpi</td>
    <td>Medium density screens, around 160 dpi
</td> 
  </tr>
    <tr>
    <td>android-hdpi</td>
    <td>High density screens, around 240 dpi
</td> 
  </tr>
    <tr>
    <td>android-xhdpi</td>
    <td>Extra-high density screens, around 320 dpi
  </tr>
    <tr>
    <td>android-xxhdpi</td>
    <td>Extra-extra-high density screens, around 480 dpi
  </tr>
      <tr>
    <td>android-xxxhdpi</td>
    <td>Extra-extra-extra-high density screens, around 120 dpi
  </tr>
</table>