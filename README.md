# LN_loader
Loader para los proyectos de lanacion.com

##Cargar Libreria spin
```
<script src="http://especiales.lanacion.com.ar/multimedia/proyectos/LN_loader/js/spin.min.js"></script>
```


##Cargar DIV contenedor + script de configuración
```
<!-- LN LOADER -->
<div id="foo" style="width: 60px; height: 120px; position: relative; left: 50%; top: 0; margin-left:-30px; background-image: url('http://especiales.lanacion.com.ar/multimedia/proyectos/LN_loader/ln.svg'); background-repeat: no-repeat; background-position: center;"></div>

<script>var opts={lines:40,length:2,width:1,radius:25,corners:0.5,rotate:1,color:"#006998",speed:1,trail:60,shadow:false,hwaccel:false,className:"spinner",zIndex:2000000000,top:0,left:0};var target=document.getElementById("foo");var spinner=new Spinner(opts).spin(target);</script>
<!-- LN LOADER -->
```


[Ver Ejemplo](http://especiales.lanacion.com.ar/multimedia/proyectos/LN_loader/ln_loader.html)
