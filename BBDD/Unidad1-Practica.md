

**A partir del siguiente enunciado se desea realizar una aproximación al modelo relacional. Identifique el nombre de las diferentes tablas que se necesitarán, columnas de cada tabla y sus tipos de datos, alguna restricción a los datos, posible relación entre tablas, …**

Una empresa vende productos a varios clientes. Se necesita conocer los datos personales de los clientes (nombre, apellidos, dni, dirección y fecha de nacimiento).

1era Tabla:
Clientes

PK: DNI
Atributos: Nombre, apellido 1, apellido 2, fecha de nacimiento.
Atributo Compuesto: Dirección (Calle, Puerta, Poblacion, Ciudad, CP)

Cada producto tiene un nombre y un código, así como un precio unitario.
Tabla Productos:

PK: ID productos,
Atributos: Nombre, precio.

Un cliente puede comprar varios productos a la empresa, y un mismo producto puede ser comprado por varios clientes.

Los productos son suministrados por diferentes proveedores. Se debe tener en cuenta que un producto sólo puede ser suministrado por un proveedor, y que un proveedor puede suministrar diferentes productos.


De cada proveedor se desea conocer el NIF, nombre y dirección”.

Tabla Proveedores: 
PK: NIF
Atributo: Nombre
Atributo Compuesto: Dirección

