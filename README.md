# cfdiDescargaMasiva
CFDI Descarga Masiva XML. Script PHP para descargar CFDI.

# Requerimentos:
  - Servidor PHP
  - Sesión iniciada en el sitio portalcfdi.facturaelectronica.sat.gob.mx.
  - Uso de herramientas de desarrollador para obtener secciones del sitio actual.
  
# Configuración:
  - Iniciar el servidor PHP
  - Iniciar sesión en el sitio portalcfdi.facturaelectronica.sat.gob.mx.
  - Realizar el filtro de la sección de los XML a visualizar y seleccionar el año y mes que se necesita descargar.
  - Abrir herramientas de desarrollador y copiar el contenido del div class='DivPaginas'.
  - Guardar el contenido copiado en el archivo invoice.txt.
  
# Ejecución:
  Teniendo el contenido en el archivo invoice.txt, ejecutar el script de PHP desde URL o línea de comandos.
  El script comenzara abrir las pestañas de cada XML correspondiente al contenido de invoice.txt y los guardará en la
  carpeta de descargas.
