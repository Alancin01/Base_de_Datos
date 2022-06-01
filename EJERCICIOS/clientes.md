![image](https://user-images.githubusercontent.com/103066839/170978299-d99eb90b-7869-42c3-b61e-701f365bca7c.png)

CREATE DATABASE empresa ;
USE empresa;

CREATE TABLE clientes(
  identificacion_cliente INT UNSIGNED PRIMARY KEY,
  nombre_cliente VARCHAR(50) NOT NULL,
    apellido_cliente VARCHAR(50),
    direccion_cliente VARCHAR(100),
    fecha_nacimiento DATE NOT NULL	
  );
CREATE TABLE proveedores(
  nit_proveedor INT UNSIGNED PRIMARY KEY,
    nombre_proveedor VARCHAR(50) NOT NULL,
    direccion_proveedor VARCHAR(100) 
  );
CREATE TABLE productos(
  codigo_producto INT UNSIGNED PRIMARY KEY,
    nombre_producto VARCHAR (50) NOT NULL,
    nit_proveedor1 INT UNSIGNED,
    FOREIGN KEY (nit_proveedor1) REFERENCES  proveedores(nit_proveedor)
  );
CREATE TABLE clien_prod (
  identificacion_cliente1 INT UNSIGNED NOT NULL,
    codigo_producto1 INT UNSIGNED NOT NULL,
  FOREIGN KEY (identificacion_cliente1) REFERENCES clientes(identificacion_cliente),
    FOREIGN KEY (codigo_producto1) REFERENCES productos(codigo_producto)  	
  );
  
  https://www.db-fiddle.com/f/gJymRXRuYS5DGALLMJU8PC/0