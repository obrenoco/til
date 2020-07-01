## Shortcuts-01

# On VSCode,

Apperently if you write `.class-name`, and press `tab`,
it creates you **a class**
```
 .class-name      <!-- press tab -->
 .
 .
<div class="class-name"></div>`  <!-- div created -->
```


But if instead you use `#id-name`, and **creates an id** `tab`:
```
 #id-name      <!-- press tab -->
 .
 .
<div id="id-name"></div>`  <!-- div created -->
```
it creates and `id`.

=> So `.` for `class` and `#` for `id`



You can use `+` to create **two classes**:
```
 .my-class+your-class             <!-- press tab -->
 .
<div class="my-class"></div>      <!-- div created -->
<div class="your-class"></div>    <!-- also created-->
```


You can just write them together to create **ONE div with several classes**:
```
 .my-class.your-class                    <!-- press tab -->
 .
 .
<div class="my-class your-class"></div>  <!-- div created -->
```


you can **multiply**:
```
 h1.my-class*4                   <!-- press tab -->
 .
 .
<div class="my-class"></div>  <!-- 4 divs created -->
<div class="my-class"></div>  
<div class="my-class"></div>  
<div class="my-class"></div>  
```



you can create **one element inside the other** with `>`, like this:
```
ul>li.my-list*4                  <!-- press tab -->
 .
 .
<ul>                            <!-- ul + 4 li w/ .my-list -->
    <li class="my-list"></li>
    <li class="my-list"></li>
    <li class="my-list"></li>
    <li class="my-list"></li>
</ul> 
```


That's it !
bye

[Linkedin](https://www.linkedin.com/in/brenoromeiro/)
