# Administración de landings en Vtex

[Guía para la creación de una landing](https://github.com/grupo-exito-ecommerce/exito-vtex-doc/blob/master/directory/landing-creation/landing-creation.md)  
[Descarga](https://github.com/grupo-exito-ecommerce/exito-vtex-doc/blob/master/resources/examples/landing/new-landing.html) el archivo HTML base para la creación de una landing

**Links de Bootstrap**

|Bootstrap| Url | Documentación
|--|--|--|
|Bootstrap v3.3.5 (Vesion Exito)| [/arquivos/bootstrap.exito.min.css](https://exitocol.vteximg.com.br/arquivos/bootstrap.exito.min.css)  | |
|Bootstrap v3.3.7| [/arquivos/bootstrap.3.3.7.min.css](https://exitocol.vteximg.com.br/arquivos/bootstrap.3.3.7.min.css) | [Doc](https://getbootstrap.com/docs/3.3/getting-started/) |
|Bootstrap v4.3.1| [/arquivos/bootstrap.4.3.min.css](https://exitocol.vteximg.com.br/arquivos/bootstrap.4.3.min.css) | [Doc](https://getbootstrap.com/docs/4.3/getting-started/introduction/)


#### Guía de uso:
> La url que debemos de emplear al momento de armar nuestra landing debe
> de ser relativa y no absoluta, para prevenir lentitud al redirigir las urls absolutas cuando se cambien de DNS

Al momento de llamar los recursos *css* de Bootstrap  desde el sistema de archivos de vtex, estamos cargando un archivo personalizado que solo funciona si el contenido esta encerrado dentro de una clase llamada  `landing-container` esto es para que los estilos aplicados por Bootstrap no afecten al resto del sitio. 


**Bootstrap v3.3.5 (Vesion Exito)**: Esta versión de Bootstrap es la empleada actualmente en el sitio web del exito. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3NzU1MTc2MzZdfQ==
-->