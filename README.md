# Descripcion general
## Actividad
Evaluación técnica postulante a cargo de Ingeniero desarrollador

## Tipo actividad
Individual

## Tiempo para actividad
Máximo 2 horas

## Producto a evaluar
CRUD de paciente

## Aspectos a evaluar
- Conocimientos de desarrollo
- Conocimientos de Framework CodeIgniter
- Medotologías de desarrollo
- Utilización de herramientas (jQuery, Bootstrap, validaciones, helpers, etc.)

# Producto a evaluar
## Objetivo
El postulante deberá implementar un CRUD de paciente simple en framework CodeIgniter, utilizando las herramientas que disponga y desee

## Base de datos
```
#DROP TABLE IF EXISTS pacientes;
CREATE TABLE pacientes (
  id int(11) NOT NULL AUTO_INCREMENT,
  rut varchar(10) DEFAULT NULL COMMENT 'ej. 12345678-9',
  numfichaclinica varchar(255) DEFAULT NULL ,
  nombres varchar(255) DEFAULT NULL,
  apellidopaterno varchar(255) DEFAULT NULL,
  apellidomaterno varchar(255) DEFAULT NULL,
  fechanacimiento date DEFAULT NULL,
  PRIMARY KEY (id)
) 
ENGINE=MyISAM DEFAULT CHARSET=utf8;
```

# Requerimientos previos
## Framework
CodeIgniter

## Otros
- Apache / Nginx
- PHP
- MySQL
- GIT

# Consideraciónes
El proyecto se deberá trabajar localmente para luego ser subido a github
