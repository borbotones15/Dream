# Dream
Segunda entrega del proyecto DreamHome, correspondiente al ramo Prog. Base Dat. Oracle.

Como utilizar la aplicación
---------------------------


Al correr la aplicación se abre una ventana con diferentes elementos:
  -Una tabla con las propiedades agregadas hasta el momento (parte superior)
  -Varias cajas de texto y un DropdownList para rellenar o buscar datos según sea pertinente (Buscar, modificar, agregar y eliminar)
  -Botones para las diferentes acciones que la aplicación realiza:
  
	  -Buscar
  Activa el DropdownList, tornándolo visible y activo, en el está listada, toda propiedad existente en la base de datos. Una vez que se elija una, el sistema muestra sus respectivos datos en los campos TextFiel, rellenando la información.
  
	  -Nuevo
  Cambia el DropdownList por un Textfield para poder ingresar los datos de la nueva propiedad, una vez que el formulario es llenado, se debe clickear en “Registrar”.
  
	  -Vaciar
  Limpia todos los campos existentes, sean Texfiel o DropdownList.
  
	  -Registrar
  Registra la nueva propiedad que contiene lo datos ingresados.
  
	  -Modificar
  Permite modificar los atributos de una propiedad.
  
	  -Eliminar
  Permite eliminar una propiedad, siguiendo las reglas del negocio, las cuales establecen que no es posible borrar alguna entrada de la tabla propiedad, si esta esta enlazada a arriendos activos.
  
	  -Salir
  Cierra la ventana de la aplicación.
