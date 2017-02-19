# 360 WebGL Viewer Library
Ud puede seguir el ejemplo de como utilizar el viewer tal como fue implementado en el file index.html.
La libreria *360* tiene dependencia de la libreria three.js por lo que debera incluir la misma y la libreria 360.js que puede descargar aqui.
Para la configuracion del Viewer ud. debera crear una div con la clase *360Viewer* las dimensiones de la div dependeran de las propiedades css que se le asignen, luego debera indicar la imagen 360 que desea renderizar en dicha div mediante el atributo *data-image* y la velocidad a la cual desea que gire la camara automaticamente mediante el atributo *data-velocity*, aqui debera tener en cuenta que *0.1* es rapido, *0.01* es lento y *0* elimina por completo la funcionalidad automatica. 
