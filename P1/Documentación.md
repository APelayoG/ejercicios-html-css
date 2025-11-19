# 1. Proceso de desarrollo para generar la plantilla de inicio con parcel 
Creación de la plantilla con parcel, y creación manual de las carpetas y archivos HTML necesarios para el proyecto 
![[Pasted image 20251029230607.png]]

# 2. Definición de entornos de producción y desarrollo
# 3. Soporte a navegadores antiguos
# 4. Utilización de pre/postprocesadores
## Instalación de PostHTML
Consideré conveniente el uso de PostHTML ya que me facilitaría crear una barra de navegación para la página web. Para instalarlo seguí los pasos ya establecidos, ejecutar el código *npm i -D posthtml-include*
![[Pasted image 20251116001732.png]]
Para posteriormente crear el fichero *.posthtmlrc*, al que le añadí el código:
*{
 "plugins": {
  "posthtml-include": {"doctype": "HTML 5"}
 }
}*
para que permitiese introducir otros códigos html. 
# 5. Dependencia externa
# 6. Semántica y accesibilidad
# 7. Creación y publicación a Git y Github
# 8. Publicación a internet
