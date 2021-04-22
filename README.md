# Accenture
Prueba Backend Jr Carlos Barrios

Hola! Aqui te dejo el link para clonar el proyecto!

https://github.com/CarlosBrrs/Accenture.git

He usado una base de datos en memoria con:
  usuario: accenture
  password:

RequestPath: "/factura" 
HTTP POST:  
Los jsons de entrada de ejemplo pueden ser:

{    
  "nombreCliente":"Carlos Barrios",    
  "direccionCliente":"Csrrera 20 #02-47",    
  "productosInventario":"camisa , bermuda, gorra, zapatos",    
  "cantidadProductos":"1,2,1,5",    
  "precioUnitarioProductos":"50000,20000,40000,10000"
}

{    
  "nombreCliente":"Rafael López",    
  "direccionCliente":"Calle 80 #22-8B",    
  "productosInventario":"camisa , bermuda, gorra, zapatos",    
  "cantidadProductos":"0,1,1,1",    
  "precioUnitarioProductos":"50000,20000,40000,10000"
}

A partir de estos como ejemplo, y modificando los valores de la llave "cantidadProductos", sin cambiar la cantidad de valores 
se pueden comprobar:

    HTTP DELETE con Path: "/factura/idPrestamo"
    HTTP PUT con Path: "/factura/idPrestamo" y el cuerpo json a modificar, por ejemplo, modificar el registro 2:
    
    "/factura/2"
    
    {    
      "nombreCliente":"Rafael López",    
      "direccionCliente":"Calle 80 #22-8B",    
      "productosInventario":"camisa , bermuda, gorra, zapatos",    
      "cantidadProductos":"5,2,1,1",    
      "precioUnitarioProductos":"50000,20000,40000,10000"
    }
    
