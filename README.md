# **Cotizador-Seguros**
Aplicacion Web de un cotizador de seguros


## **Objetivo**
Desarrollo de un sistema que permita a productores o publico en general, a realizar una cotización de Seguros para luego, en otra aplicación, solicitar la Póliza de seguros.

## **Enunciado**
En esta primera instancia, se desarrollara la aplicación con solo dos secciones o ramas, Seguro de Hogar (Combinado Familiar) y Seguro de Accidentes Personales.

Las cotizaciones las podrán realizar los Brokers y cualquier persona que acceda a la web (sin necesidad de login).

Los usuarios de la plataforma serán: Administrador, Empleado, Productor y Usuario Publico.
El login será requerido para los Administradores, Empleados y Productores. 

Los Administradores podrán realizar cualquier actividad.
Los Empleados podrán dar de alta usuarios Broker, actualizar la tasa de cobertura de las secciones, para el calculo de la prima, y ver la cotizaciones realizadas.
Los Brokers tendrán acceso a sus cotizaciones realizadas.

### **Las acciones de esta primer etapa seran:**
- Login/Logoff
- Generación de usuarios
- Listado de Cotizaciones
- Actualización de tasas

## **Las entidades son:**

- Usuarios
	- Administrador
	- Empleado
	- Productor

- Secciones
	- Hogar
	- Accidente

- Cotizaciones


## **Las propiedades de las entidades son:**

- Usuario
	- Id
	- Email (nombre de usuario)
	- Password
	- Nombre
	- Apellido
	- FechaAlta

- RamaHogar
	- Id
	- Descripcion
	
- RamaAccidente
	- Id
	- Descripcion

- CotizacionHogar
	- Id
	- Descripcion
	- NombreAsegurado
	- TelefonoAsegurado
	- EmailAsegurado
	- FechaCotizacion
	
- CotizacionAccidente
	- Id
	- UsuarioId
	- Descripcion
	- NombreAsegurado
	- TelefonoAsegurado
	- EmailAsegurado
	- FechaCotizacion

## **Definiciones**

- Prima: es el costo del seguro, valor técnico.
- Premio: es el valor del seguro, esta conformado por la prima mas los impuestos y gastos.
- Productor: es el nexo entre el asegurado y la compañía de seguro.
- Otras secciones o ramas: Automotor, Comercio, de Vida, Saud, etc.
