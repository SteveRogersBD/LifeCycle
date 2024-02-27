<H1> LifeCycle of Android Apps</H1>
![Android-Activity-Lifecycle](https://github.com/SteveRogersBD/LifeCycle/assets/147460804/2bad7b26-b6f0-4d98-ac7f-16073c52c099)


<H2> Toast</H2>
Toast.makeText(this, "onStart()", Toast.LENGTH_SHORT).show();
-Toast.makeText(): This is a static method used to create a new Toast object.
-this: The first parameter is the context. In this case, it's assumed to be called from within an Activity or Service class, where "this" refers to the current context of the Activity or Service.
-"onStart()": This is the message text that will be displayed in the toast.
-Toast.LENGTH_SHORT: This specifies the duration for which the toast will be displayed. Toast.LENGTH_SHORT is a constant indicating a short duration, typically around 2 seconds.
-show(): This method displays the Toast message on the screen.

<H3> Another way of creating toast</H3>
Toast toast = Toast.makeText(this,"SecondCreate()",Toast.LENGTH_SHORT); <br>
        toast.setGravity(Gravity.CENTER,0,0);  //placement of the text <br>
        toast.show(); <br>
