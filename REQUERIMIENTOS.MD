# DOCUMENTO ESPECIFICACION DE REQUERIMIENTOS INSTITUCION EDUCATIVA LOS LAURELES

## 1. INTRODUCCION:

### Sistematizar la forma de organización de información de la institucion en una base de datos, esta será utilizada para el manejo de los datos de los estudiantes y sus respectivas notas, ademas de darle la oportunidad a los padres de familia tener acceso a las notas de los estudiantes.

## 2. PROPOSITO:

### Facilitar al cliente el manejo de la información y dar a conocer al final de trimestre de manera precisa las notas y boletines de los estudiantes.

## 3. ALCANCE:

### Este proyecto está con base al desarrollo de un software y apartir de necesidad de nuestro cliente, lo primordial es darle el mejor funcionamiento la institucion de nuestro cliente que se completará con una serie de fases para su desarrollo y funcionamiento. El proyecto se dirige al sector educativo, en los cuales se busca sistematizar procesos de control de notas, en la mayoría de los casos para el óptimo funcionamiento del sistema se requiere de mejoras en la infraestructura tecnológica y adaptación de los usuarios al sistema,también la institución según sea su situación ha de invertir en la infraestructura tecnologica que garantice un óptimo funcionamiento del sistema.

## 4. DEFINICIONES, ACRONIMOS Y ABREVIATURAS:
### SIA – Sistema Integral Académico
### BD – Bases de datos
### UML – Lenguaje de Modelado Unificado
### IEEE – Institute of Electrical and Electronics Engineers
### Sistema ABC –Sistema altas, bajas y consultas
### SEP – Secretaría de Educación Pública.

# ---ESTRUCTURA DE DOCUMENTO---

#### 1. INTRODUCCION

### Este es un documento de especificacion de requerimientos para un software que se va encargar de Sistematizar la forma de organización de información de la institucion en una base de datos, esta será utilizada para el manejo de los datos de los estudiantes y sus respectivas notas, ademas de darle la oportunidad a los padres de familia tener acceso a las notas de los estudiantes.

#### 1.1.	PROPÓSITO

### Facilitar de manera clara y concisa los requeriminetos de este software al cliente para manejo de la información y dar a conocer al final de trimestre de manera precisa las notas y boletines de los estudiantes.

#### 1.2.	ÁMBITO DEL SISTEMA

### Este es un software que va ser utilizado en el sector educativo.

#### 1.3.	DEFINICIONES, ACRÓNIMOS Y ABREVIATURAS

* SGBD	Sistema Gestor De Base De Datos
* JAVA	Lenguaje de Programación

#### 1.4. REFERENCIAS

#### TITULO----------NÚMERO--------------FECHA
### IEEE GUIDE FOR SOFTWARE REQUIREMENTS SPECIFICATIONS IEEE	Std 830-84	1994
### OMG Unified Modeling Language Specification Version 1.4	Formal/2001-09-67	2001

#### 2. DESCRIPCIÓN GENERAL

### 2.1. PERSPECTIVA DEL CLIENTE 

#### Con este software se lograra llevar el control total de los informes de los profesores con respecto a las notas de los estidiantes, redactar boletines y guardar todo en una base de datos para posteriores usos

### 2.2. FUNCIONES DEL PRODUCTO

## SOFTWARESOL:
* Gestión de funcionarios
* Gestión de alumnos
* Gestión de padres de familia
* Gestión de base de datos

##### *Diagrama de descomposición de requerimientos de nombre del producto.*

#### ESTRUCTURA DE LOS REQUERIMIENTOS
#### Cada requerimiento tendrá su detalle con la siguiente información:
* Introducción
* Entrada
* Proceso
* Salidas
* Requerimientos específicos no funcionales

### GESTIÓN DE FUNCINARIOS
* Registrar funcionario
* Actualizar funcionario
* Eliminar funcionario
* Consultar funcionarios
* Generar informe
##### *Diagrama de descomposición gestión de productos.*

### 2.2.1. GESTIÓN DE CLIENTE EJEMPLO
### Es un conjunto de requisitos relacionados con la gestión de usuario, se centra en los registros, actualización, eliminación, consulta y generar informe  de los funcionarios.

### 2.2.1.1	Registra funcionarios.

### INTRODUCCIÓN 
### Su función consiste en registrar un nuevo funcionario en la base de datos. Para ello el funcionario debe ingresar sus datos en un formulario el cual está sincronizado con una base de datos.

### ENTRADA
*	Id del funcionario
*	Nombre del funcionario
*	Correo del funcionario
*	Teléfono del funcionario
*	Dirección del funcionario

### PROCESO
#### Una vez haya accedido a esta utilidad del sistema se introducen los datos de funcionario, estos serán validados por el sistema, comprobando la existencia previa del funcionario en la base de datos, o en su defecto generando un nuevo registro. Una vez realizada se presenta en pantalla un mensaje de confirmación de la operación.

#### Cualquier error que se produzca durante el proceso debe ser notificado al usuario mediante un mensaje descriptivo en pantalla.

### SALIDA
* Registro de la base de datos
* Mensaje de confirmación con el resultado del nuevo registro en la base de datos ok.
* Requisitos específicos no funcionales.

### Base de datos:
#### El registro de los datos en la BD se bebe realizar en un máximo de 2 segundos.

### 2.2.1.2. Actualizar el funcionario
* Introducción
* Entrada
* Proceso
* Salida
* Requerimientos no funcionales

### 2.2.1.3. Eliminar funcionario
* Introducción
* Entrada
* Proceso
* Salida
* Requerimientos no funcionales

### 2.2.1.4 Consultar funcionario
* Introducción
* Entrada
* Proceso
* Salida
* Requerimientos no funcionales

### 2.2.1.5. Generar informe
* Introducción
* Entrada
* Proceso
* Salida
* Requerimientos no funcionales

## 2.2.2. GESTIÓN DE FUNCIONARIOS
## 2.2.3. GESTIÓN DE ALUMNOS
## 2.2.4. GESTIÓN DE PADRES DE FAMILIAS
## 2.2.5. GESTIÓN DE REPORTES FINALES

## 2.3. CARÁCTERÍSTICAS DE LOS USUARIOS
#### Tener conocimiento básico en informática y conocer la funcionalidad de algunas.

## 2.4.RESTRICCIONES
### 2.4.1 Políticas de la entidad
* Funcionalidad de la aplicación lunes a domingo 24 horas
### 2.4.2. Limitaciones de Hardware
### 2.4.3. Operaciones paralelas
### 2.4.4. Funciones de auditoria 
* N/A
### 2.4.5. Funciones de control
* No se contempla
### 2.4.6. Lenguaje de programación

### 2.4.7. Protocolos de comunicación
#### Los protocolos de comunicaciones entre los diferentes nodos de la infraestructura hardware de soporte serán los siguientes:
* HTTPS Para conexiones con el servidor web
* TCP/IP a nivel físico
* Ethernet 802.3 a nivel eléctrico

### 2.4.8. Requisitos de fiabilidad
### 2.4.9. Criticidad de la aplicación
* Si se cae el internet por ejemplo que hacer para generar un respaldo para que la información no se pierda
### 2.4.10. Consideraciones de seguridad
* Si se requiere que el usuario se registre, contraseñas robustas etc

### 2.5. SUPOSICIONES Y DEPENDENCIAS
* Se asume que los requerimientos aquí descritos son estables y satisfacen las necesidades del sistema

* El sistema será genérico para poderlo ejecutar en cualquier dispositivo móvil

## 2.6.	REQUERIMIENTOS FUTUROS

## 3.1. INTERFACES EXTERNAS

### 3.1.1. Interfaces de usuario
### 3.1.2. Interfaces de hardware
### 3.1.3. Interfaces de software
### 3.1.4. Interfaces de comunicación

## 3.2. REQUISITOS DE RENDIMIENTO
### 3.2.1. Números de usuarios conectados simultáneamente

## 3.3. REQUISITOS ESPECIFICOS
### 3.3.1. Informe de análisis de software
### 3.3.2. Informe de calidad del software
### 3.3.3. Informe de gestión de riesgo
### 3.3.4. Informe de gestión de seguridad del software




















