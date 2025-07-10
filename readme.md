# Te lo Vendo - Sitio Web

##Integrantes:

-María Teresa de la Fuente
-Roberto Escobar Vivallo
-Esteban Varela
-Gonzalo Román Reyes

## Ruta de repositorio:https://github.com/mt-dafonte/te-lo-vendo


## Actividad Metodologías de organización y modularización de estilos -- 03.07.2025

1.Formulario de contacto 
	Formulario de contacto ya estaba incorporado.

2. Metodología BEM
	El proyecto ya tenía la metodología BEM aplicada, tanto en los archivos .html como en el archivo styles.css. Se revisó que las clases siguieran la estructura bloque__elemento--modificador.

3. Convención de nombres
	Se revisó que todas las etiquetas y clases estuviesen en inglés, respetando buenas prácticas de consistencia y legibilidad.

4. Revisión y ajustes de estilos
	- Se detectó que el color asignado a --primary-color y a --dark-color era el mismo, por lo tanto este último se cambió a un color más oscuro.
 	- Se aclaró el fondo de los íconos de redes sociales en el footer para mejorar el contraste.
	- Se oscureció el color de texto de los -feature__text de index.html y about-us.html para mejorar la legibilidad.
	- Se agregaron líneas de contorno a los bloques .feature de index.html y about-us.html para mejorar su separación del fondo.


5. Organización y modularización de estilos
	a) Se separó el contenido del archivo styles.css, creado inicialmente, en los siguientes 4 archivos:
	 _base.scss (variables y estilos base)
	 _layout.scss (estructura general)
	 _components.scss (buttons, cards, form, modals, etc)
	 _sections.scss (secciones específicas como: hero, presentation, featured, etc)

	b) Estos 4 archivos se importaron al archivo main.scss que generó el archivo main.css
	c) El archivo main.css fue vinculado en todos los archivos .html reemplazando al archivo styles.css

