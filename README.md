# Web-R3D
Sitio web R3D La Serena, Chile

Esta página web corresponde a un taller realizado para la asignatura de **Herramientas de desarrollo web** de 
IPCHILE sede La Serena con el docente Roberto Delgado.

## Codificación
Esta web fue desarrollada en **HTML5**, **CSS3** y **Javascript**.
Para realizar el layout se realizó una investigación por la web buscando algun diseño innovador y a su vez inspirador. 
Una vez encontrado un diseño a gusto, se procedió a crear la **Style Guide** (guía de estilo) la cual sirve de apoyo 
al programador para realizar la maquetación básica. Esta _Style Guide_ fue realizada por un diseñador profesional el cual
decide la paleta de colores, tipo de fuente y todo lo relacionado con el diseño. Se puede revisar la 
[Style Guide R3D](http://www.lalvarado.cl). Teniendo esto podremos empezar a desarrollar nuestra página web.

# Scripts
Los scripts que se utilizaron son los siguintes:
```javascript var ran;
ran = Math.round(Math.random()*5000);
document.write("Usted es el visitante " + ran + " de esta página.");```


## reloj-digital.js
```javascript function startTime(){
    today=new Date();
    h=today.getHours();
    m=today.getMinutes();
    s=today.getSeconds();
    m=checkTime(m);
    s=checkTime(s);
    document.getElementById('reloj').innerHTML=h+":"+m+":"+s;
    t=setTimeout('startTime()',500);}
    function checkTime(i)
    {if (i<10) {i="0" + i;}return i;}
    window.onload=function(){startTime();}```
