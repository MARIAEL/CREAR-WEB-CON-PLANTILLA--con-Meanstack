#1.- Crear carpeta nueva.  

Ir a **EQUIPO** >> ```C:\Bitnami\meanstack-3.2.1.-0\apps``` y crear una nueva carpeta (pe. corlate)  
También la podemos crear desde el terminal con el comando ```mkdir``` seguido del nombre de la carpeta. (Hemos de estar dentro de ```apps```    


#2.- Yo angular  

Ir al terminal de Bitnami y situarnos en la carpeta que hemos creado (cd apps / cd corlate) entonces escribimos: 
```yo angular```  
Cuando termine escribimos ```ls``` y comprobamos que ya tiene contenido.  
Arrancamos el servidor ```grunt serve```  


#3.- Sublime Text  

Arrastramos a Sublime Text la carpeta ```app``` de Corlate (que nosotros hemos creado y Yeoman ha generado la estructura).  
También arrastramos la plantilla Corlate  


#4.- Abrir y revisar la estructura de los index.html de ambas carpetas.  

Revisamos la estructura del **header** y del **footer** de ambos archivos.  
Hemos de copiar del archivo **index.html** de la plantilla el **header** y lo pegamos en el **index.html** de nuestra web.  
Hacemos lo mismo con el **footer**  


#5.- Copiar links y archivos de css de la plantilla a nuestra web.  

Hemos de copiar los links del css de la plantilla a nuestra web, pegándolos en nuestro index,   
detrás de ```<!-- build:css(.tmp) styles/main.css -->```  
y siempre antes de ```<link rel="stylesheet" href="styles/main.css">```  
Quedarán así:  

![](http://grabilla.com/0611e-14e2a806-0f50-4d04-b884-26fe9fdffe10.png)


Copiamos el contenido de la carpeta **css** y lo pasamos a la nuestra de **styles**  

![](http://grabilla.com/0611e-ce227581-72de-4a00-b4bb-373960f129cf.png)



#6.- Copiar links y archivos de js de la plantilla a nuestra web.

También copiamos los links **js** y los pegamos detrás de ```<!-- endbuild -->```  

Quedarán así:  


![](http://grabilla.com/0611e-c0a5106f-9823-43ca-8bba-c378fceb478c.png)  

Ahora copiamos los **archivos** de dentro del **js** de la plantilla y lo pegamos en la carpeta **scripts** de nuestra web.  


![](http://grabilla.com/0611e-bc07f941-2b5e-4918-8e50-e3dd1c9037cf.png)



#7.- Copiar resto de archivos de la plantilla a nuestra web.

Las **imágenes** las copiamos y pegamos de un sitio al otro  


![](http://grabilla.com/0611e-7923346a-eac0-49f5-b6ec-a1838959b7ca.png) 


La carpeta **fonts** la copiamos entera y la pegamos en la nuestra  


![](http://grabilla.com/0611e-7715bce2-f985-41b2-be4e-86ca17712e8c.png)



#8.- Redireccionar archivos.  

Ahora debemos redireccionar los archivos cambiando donde ponía **css** --> ponemos **styles**  

![](http://grabilla.com/0611e-f5a1b471-56d3-40d8-9e4c-256e2f10156f.png)


Y donde ponía **js** poner **scripts**  

![](http://grabilla.com/0611e-dfd6fc44-3f0b-4858-9044-2c306b53a28d.png)



#9.- Reiniciar el servidor.

Después de este proceso REINICIAR EL SERVIDOR  

```Ctrl C``` y ```grunt serve```  


#10.- Copiar contenidos  

Vamos a **index.html** de la plantilla corlate y copiamos el contenido que haya entre el **header** y el **footer.  
Lo pegamos en **main.html** también entre el **header ** y el **footer**.  

Lo siguiente será traducir el menú del navegador y modificar los ```href``` de la ```navbar```  

![](http://grabilla.com/0611e-1b55e159-19da-4ac5-90f8-a11b120ba037.png)


Ahora pegamos el contenido de **About us** (de la plantilla) a nuestro **Nosotros**  

Crearemos las páginas que nos faltan para tener las mismas que las de la plantilla.  
Para ello ejecutamos en la terminal de Bitnami ```yo angular:route servicios```(pe.)  
Iremos copiando los respectivos contenidos de las plantillas a las nuevas carpetas.  


#11.- Github desktop  

Arrastramos la nueva carpeta con su contenido desde ```Bitnami/meanstack-3.2.1-0/apps/corlate``` hasta github desktop (Si la primera vez no lo permite intentarlo una segunda vez)  
Ponemos un comentario relativo a la acción realizada y **publish**.  

Cada vez que realicemos un cambio significativo es conveniente poner un comentario y pulsar **commit to master**. 

![](http://grabilla.com/0611f-94cd96b4-8161-4343-b910-35cea1a0d593.png)
