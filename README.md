# AndroidStudio

## Training Material
https://codelabs.developers.google.com/codelabs/android-training-layout-editor-part-a/index.html?index=..%2F..android-training#2


Notes:
## Adding elements to the screen.
- Open activity_main.xml
- Select the type
- Drag the element to the screen.
- Adjust proprties
- Set Text to references from the resources strings..
- To add events, add it to the activity_main.xml, for example: android:onClick="showToast" under the xml referent to the object;
- "Alt+Enter" over the text on activity_main.xml to create the method on MainActivity.java
- Adding access to a object create in the screen.
  - Create a private object inside the Class: example: **private TextView mShowCount;**
  - under onCreate method of the application: set the new object to the existing object:
  - Example: **mShowCount = (TextView) findViewById(R.id.show_count);**



## Strings
String are defines on res\values\strings.xml  
On code to use a string, R.string.string_name  
On activity_main.xml to use string "@strong/string_name"  




