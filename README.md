# wordpress-Clinica
## Instalar el tema en otro WordPress

El archivo `clinica-alma.zip` contiene el tema instalable. En WordPress 6.2 o
superior, con PHP 7.3 o superior y la extension `mbstring`, abre **Apariencia >
Temas > Agregar nuevo > Subir tema**, selecciona el ZIP y activalo. La portada
con sus secciones y la pagina de recepcion forman parte del tema. Al activarlo
se crea la pagina `recepcion-citas` si no existe; no se modifica una pagina
existente con ese slug. Si existe un conflicto, WordPress muestra un aviso y
debes resolverlo desde **Paginas**.

El ZIP no incluye la base de datos ni las solicitudes o contrasenas de este
sitio. Para migrar datos existentes se requiere una copia de la base de datos,
ademas de los archivos correspondientes. Al cambiar de tema, las solicitudes
siguen en la base de datos, pero la interfaz de recepcion y su funcionalidad
solo estan disponibles mientras este tema esta activo.
