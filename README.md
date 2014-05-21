ims-frontpage
=============

Repository for the frontpage of ims.wesleyan.edu for use by office managers.

To add a new widget, append 
```
 <div class="box">
   <h2 class="box-hd">{widget title}</h2>
   <div><a href="{new link}>" target="_blank"><i class="{an icon class} icon-2x"></i> {link name}</a></div>
 </div>
```
to the end of the div with the .row class.
To see available icons open up icomoon/demo.html. If you want to make a new icon use the icomoon web app.
If things get crowded and you want to increase the number of widgets per row, change the width attribute of .box in css/main.css to 22% from 31%.
