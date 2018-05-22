# Tarea

Tu tarea una vez acabado el tercer módulo consiste en:

*   Crear un proyecto llamado Modulo3NombreApellido donde Nombre sea tu nombre y Apellido tu primer apellido. Ejemplo: Modulo3PabloRuiz
*   En el proyecto deberá estar organizado por paquetes de modo que tengas, al menos, los paquetes _clase_, _interf_ y _lanzador_.
*   Dentro del paquete _lanzador_ deberás crear una clase llamada _Principal_. En esta clase estará el método _main_.
*   Vamos a modelizar un tienda de bicicletas.
    *   Tendrás una clase llamada Bicicleta
    *   Todas las bicicletas tendrán dos campos comunes: color (String) y precio (double).
    *   Las subclases de bicicletas existentes podrán ser únicamente Montaña, Paseo o Tandem.
    *   En la clase bicicleta deberás sobreescribir el método toString de Object haciendo que diga el color y precio de la bicicleta.
    *   Quiero que las bicicletas implemente el método pintar, que lo que hará será cambiar el color pero me interesa que este método pintar también se pueda aplicar a otras posibles modelizaciones futuras que pudiera hacer, no debe ser exclusivo de las bicicletas. Además quiero que el coste de pintar (lo que sea) sea fijo y sea 90.
    *   Todos los campos de todas las clases deberán seguir los principios de encapsulamiento.
    *   La clase Bicicleta deberá tener un único constructor a través del cual se establezca el valor del color y precio.
    *   En la clase Principal deberás crear una lista con todas las bicicletas que tengas en la tienda. En este momento tienes 2 bicicletas de montaña, 1 bici de paseo y 2 tandems. Crea los objetos y añádelos a la lista. Posteriormente interacciona con ellos y al final recorre la lista para llamar al método toString de cada objeto.

